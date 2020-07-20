# Genetic Algorithms

Hello. Thank you for being here. This repository belongs to the youtube videos [What are Genetic Algorithms](https://youtu.be/uQj5UNhCPuo) and [Genetic Algorithm from Scratch in Python](https://youtu.be/nhT56blfRpE).
If you haven't seen it, please consider watching part one of this series, to get a better understanding of this code.

<p align="center">
  <a href="https://youtu.be/uQj5UNhCPuo" target="_blank">
    <img src="http://i3.ytimg.com/vi/uQj5UNhCPuo/hqdefault.jpg" alt="What are Genetic Algorithms">
  </a>
</p>

## Content

This repository contains the codebase I used to do the comparison between the stupid brute-force attempt to solve the Knapsack problem and the implementation of the genetic algorithms. 

The codebase is structured into three modules: `algorithms`, `problems`, and `utils`.

Inside of algorithms you find the implementation of the brute-force approach and the non-problem-specific parts of the implementation of the genetic algorithm.

`problems` contains all problem-specific parts related to the Knapsack problems, like the definition of `Things` and the problem specific fitness function for the genetic algorithm.

`utils` simply contains a utility function I wrote myself to measure time using a context manager. (https://book.pythontips.com/en/latest/context_managers.html)

`genetic_algo.py` uses the brute-force approach to find the best solution for a given Knapsack problem and tries to find the same solution using the genetic algorithm and compares the performance.

`bruteforce_time.py` and `genetic_time.py` compare the needed time a brute-force or genetic algorithm needs for a given number of items. (Be careful the brute-force approach gets slow very fast.) 

## Contribution

Corrections and additions to the documentation to help fellow learners are always welcome.
