# Recursive-Function---Tower-of-Hanoi
Tower of Hanoi Recursive Algorithm

Introduction
This repository contains a simple implementation of the recursive algorithm for the classic problem of the Tower of Hanoi.
The Tower of Hanoi is a mathematical puzzle that consists of three pegs and a number of disks of different sizes, which 
can be slid onto any peg. The objective of the puzzle is to move the entire stack of disks from one peg to another, following specific rules.

Recursion
Recursion is a powerful programming technique that involves a function calling itself to solve a problem by breaking it down into smaller, 
more manageable subproblems. In the case of the Tower of Hanoi problem, recursion provides an elegant solution.

Algorithm Overview
The algorithm presented in this repository solves the Tower of Hanoi problem recursively. Here's a brief overview of how it works:
The problem is divided into subproblems by considering the top n-1 disks and the bottom disk as separate parts.
Move the top n-1 disks from the source peg to an auxiliary peg, using the destination peg as a temporary peg.
Move the bottom disk from the source peg to the destination peg.
Move the n-1 disks from the auxiliary peg to the destination peg, using the source peg as a temporary peg.
Repeat steps 2-4 recursively until the entire stack of disks is moved to the destination peg.

Usage
To use this algorithm, you can follow these steps:
Clone the repository to your local machine.
Navigate to the project directory.
Open the RecursiveTower.ipynb file.
Run the script.
Fill in the entry with the number of discs you want.
The script will output the sequence of moves required to solve the Tower of Hanoi problem.
Feel free to experiment with different numbers of disks and observe the steps taken to solve the puzzle.

Conclusion
The Tower of Hanoi recursive algorithm presented in this repository demonstrates the power and elegance of recursion in solving 
complex problems. By understanding and applying the principles of recursion, you can tackle a wide range of programming challenges 
efficiently. Enjoy exploring and learning from this implementation!
