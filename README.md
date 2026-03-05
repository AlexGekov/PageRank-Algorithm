# PageRank Algorithm: Implementation and Mathematical Analysis
## Project Overview
This repository contains my final project submission, focusing on the implementation and analysis of the PageRank algorithm. The primary objective is to translate the "real-world" problem of web page ranking into its mathematical counterpart and solve it using Python.
## Motivation
The project explores how search engines historically ranked web pages based on their structural importance within a network. This serves as a practical application to gain a deeper understanding of linear algebra concepts, specifically stochastic matrices and eigenvectors.
## Mathematical Foundation
This project will explore the core mathematical formulation of PageRank. The basic equation for the PageRank of a given page is:
$PR(A) = (1-d) + d \sum \frac{PR(T_i)}{C(T_i)}$
The analysis will heavily feature Markov chains, transition matrices, and the calculation of dominant eigenvectors to achieve convergence.
## Deliverables and Repository Structure
- pagerank_analysis.ipynb: The core Jupyter notebook containing all English explanations, mathematical proofs, and Python code
- .data/: A folder to hold any network graphs or simulated web structures used for testing the algorithm.
- requirements.txt: A list of external Python libraries required to run the code (e.g., NumPy, Matplotlib, NetworkX).
## Methodology
- Problem Formulation: Defining the web as a directed graph and establishing the significance of the ranking problem.
- Implementation: Building the PageRank algorithm from scratch using Python.
- Analysis: Testing the algorithm's efficiency, analyzing its computational complexity, and observing how changes to the damping factor $d$ affect convergence speed.
## Author 
Aleksandar Gekov
