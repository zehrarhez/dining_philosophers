## DINING PHILOSOPHERS PROBLEM PROJECT
<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fgithub.com%2Ftopics%2Fphilosophers-dinner-problem%3Fo%3Ddesc%26s%3Dupdated&psig=AOvVaw0MRbqE-cdFQubpps6GNBFa&ust=1703829268244000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCLjhnOm4sYMDFQAAAAAdAAAAABAD" alt="dining-philosophers" width=250>


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

* [Exploratory Data Analysis](https://www.geeksforgeeks.org/what-is-exploratory-data-analysis/)
* [Preprocessing the Data](https://www.geeksforgeeks.org/data-preprocessing-machine-learning-python/)
* [Cross Validation](https://scikit-learn.org/stable/modules/cross_validation.html)
* [Hyperparameter Tuning](https://www.geeksforgeeks.org/hyperparameter-tuning/)
* [Grid Search & Randomized Search](https://www.geeksforgeeks.org/comparing-randomized-search-and-grid-search-for-hyperparameter-estimation-in-scikit-learn/)
  

<p align="right">(<a href="#readme-top">back to top</a>)</p>




