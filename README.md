## DINING PHILOSOPHERS PROBLEM PROJECT
<img src="https://user-images.githubusercontent.com/61487831/125204793-2d29da00-e2a9-11eb-9a44-e0ba8d48bed1.gif" alt="dining-philosophers" width=400>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#dining-philosophers-problem">Dining Philosophers Problem</a></li>
        <li><a href="#time-out-approach">Time Out Approach</a></li>
        <li><a href="#effects-of-time-out-approach">Effects of Time Out Approach</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

### Dining Philosophers Problem

The dining philosopher's problem is the classical problem of synchronization which says that Five philosophers are sitting around a circular table and their job is to think and at alternatively. A bowl of noodles is placed at the center of the table along with five chopsticks for each of the philosophers. To eat a philosopher needs both their right and a left chopstick. A philosopher can only eat if both the immediate left and right chopsticks of the philosopher are available. In case if both immediate left and right chopsticks of the philosopher are not available then the philosopher puts down their (either left or right) chopstick and starts thinking again. The dining philosopher demonstrates a large class of concurrency control problems hence it's a classic synchronization problem. 

According to this problem, if all philosophers take the stick on their right, for example, they will all have a stick and they will not be able to eat. If they all try to take both of them, then the racing condition encountered in simultaneous operations will occur and whoever acts first (we have no guarantee on this) will be able to eat his meal. And maybe none of them will be able to eat because they will all get a stick. If they all leave their sticks for someone else to eat, then none of them will be able to eat. These types of problems can generally be considered as starvation problems. Accordingly, every philosopher has the possibility of eating, but it is by no means guaranteed that he will eat. For example, one of the philosophers may go hungry in any situation and never have his turn. 

Another problem encountered in the problem is deadlock. As a result of a wrong design, a philosopher who takes a single fork and waits for the other philosopher to leave the fork can crash the system. This is the second risk found in the problem.


### Time Out Approach
![image](https://github.com/zehrarhez/dining_philosophers/assets/86465805/d569fa1b-1627-4a4f-9f0a-a306df3fd6a0)

a) Timeout for Fork Acquisition:

Philosophers try to acquire both their left and right forks. If a philosopher can't acquire both forks after a certain time (timeout), they release the acquired forks and start thinking again. This prevents a philosopher from waiting indefinitely for a fork and allows others to use it.

b) Randomized Delay:

Introducing a random delay before retrying to acquire forks helps avoid simultaneous attempts by adjacent philosophers, reducing contention.

c) Asymmetric Requesting:

Philosophers could be programmed to request the right fork first and then the left one. This can break the circular dependency that leads to deadlock.

### Effects of Time Out Approach

a) Prevents Deadlock:

By releasing forks after a timeout, it prevents situations where philosophers are indefinitely waiting for a resource held by another philosopher.

b) Reduces Livelock:

Livelock occurs when philosophers keep releasing and reacquiring forks, unable to make progress. The timeout approach mitigates this by allowing a philosopher to abandon the attempt and think again.

c) Potential Starvation:

There's a risk that a philosopher might starve if the timeout is too short or if the delay mechanism favors other philosophers more frequently.

d) Increased Overhead:

Implementing timeouts and delays adds computational overhead, potentially affecting the efficiency of the solution.

e) Dependency on Timeout Duration:

The effectiveness of the solution heavily relies on the chosen timeout duration. A longer timeout might reduce contention but could increase the likelihood of starvation.

### Built With

<!-- Embedded Python Logo -->
<img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png" alt="Python Logo" width="200"/>


<!-- GETTING STARTED -->
## Getting Started

### Installation
Download the .py file and run
```sh
timeout_solution.py
```


<!-- CONTACT -->
## Contact

Zehra ÖZEREN - zehrarhezz9@gmail.com

Project Link: [Dining Philosophers Problem](https://github.com/zehrarhez/dining_philosophers/tree/main)



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Dining Philosophers Alternative Solutions](https://bilgisayarkavramlari.com/2012/01/22/filozoflarin-aksam-yemegi-dining-philosophers/)

  

<p align="right">(<a href="#readme-top">back to top</a>)</p>




