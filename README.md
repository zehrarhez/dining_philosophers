## DINING PHILOSOPHERS PROBLEM PROJECT
<img src="https://user-images.githubusercontent.com/61487831/125204793-2d29da00-e2a9-11eb-9a44-e0ba8d48bed1.gif" alt="dining-philosophers" width=250>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
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

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Built With

<!-- Embedded Python Logo -->
<img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png" alt="Python Logo" width="200"/>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Installation
Download the .py file and run
```sh
timeout_solution.py
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Zehra ÖZEREN - zehrarhezz9@gmail.com

Project Link: [Insurance Amount Prediction Project](https://github.com/zehrarhez/insurance-prediction-GBM)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Dining Philosophers Alternative Solutions](https://bilgisayarkavramlari.com/2012/01/22/filozoflarin-aksam-yemegi-dining-philosophers/)

  

<p align="right">(<a href="#readme-top">back to top</a>)</p>




