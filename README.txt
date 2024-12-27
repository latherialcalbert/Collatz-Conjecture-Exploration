# Collatz Conjecture Exploration

This repository contains the final project for my "A Conceptual Tour of Mathematics" course, where I explored the Collatz Conjecture through the lens of experimental mathematics. In this project, I used computational tools to investigate the behavior of the Collatz sequence for various starting numbers and analyze patterns that arise in its progression.

## Project Overview

The Collatz Conjecture, also known as the 3n + 1 problem, is a famous unsolved problem in mathematics. It involves a sequence defined as follows:
1. Start with any positive integer \( n \).
2. If \( n \) is even, divide it by 2.
3. If \( n \) is odd, multiply it by 3 and add 1.
4. Repeat the process indefinitely.

The conjecture posits that no matter what number you start with, the sequence will always eventually reach 1. Despite extensive computational evidence supporting this, no proof has been found.

### Course Background

In the course "A Conceptual Tour of Mathematics," we explored key branches of mathematics and their applications, from number theory to geometry and calculus. For my final project, I chose the Collatz Conjecture as it is both an accessible and intriguing topic that lies at the intersection of number theory and computational experimentation.

## Files

- **collatz_conjecture_exploration.ipynb**: The Jupyter notebook containing my exploration of the Collatz Conjecture. This includes code to generate the Collatz sequence for various starting values and visualizations of the sequences. It also explores patterns that arise from these sequences and includes an analysis of their behavior.

- **Collatz_Conjecture_Exploration_Report.pdf**: A detailed report summarizing the project, its methodology, and the results. This document provides a deeper theoretical background of the Collatz Conjecture, the approach taken in the project, and the insights gained from the computational experiments.

## Prerequisites

To run the Jupyter notebook and reproduce the results, ensure you have the following Python libraries installed:

- `numpy` for numerical operations.
- `matplotlib` for plotting and visualizing the sequences.
- `pandas` for managing the data and handling sequences.

You can install these libraries using `pip`:

```bash
pip install numpy matplotlib pandas
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/Collatz-Conjecture-Exploration.git
cd Collatz-Conjecture-Exploration
```

2. Open and run the Jupyter notebook:

```bash
jupyter notebook collatz_conjecture_exploration.ipynb
```

3. Explore the Collatz sequence for various starting values, generate plots, and analyze the conjecture’s behavior.

## Insights and Results

- The notebook includes visualizations of Collatz sequences starting from different integers and provides insights into the time it takes for the sequences to reach 1.
- Patterns, such as the length of the sequence and the number of steps required, are examined.
- While no general proof has been found for the conjecture, computational experiments reveal that the conjecture holds for a vast range of numbers.

## License

This project is open-source and available under the MIT License. 