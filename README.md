# CS 1501 - Lab #6 (Dynamic Programming)[^1]

## Table of Contents

- [Overview](#overview)
- [Tasks](#tasks)
- [Testing](#testing)
- [Submission](#submission)

## Overview

 __Purpose__: In this lab, you will complete the implementation of two dynamic-programming problems.

The starter files have been provided to you with the following contents:

- `KnapSack.java` - The 0/1-Knapsack dynamic-programming problem for you to finish solving.
- `ChangeMaker.java` - The Change-Making dynamic-programming problem for you to finish solving.
- `ExpectedOutputs` - The expected outputs for the programs.
- Three input files for each problem.

## Tasks

In this lab, we will be solving two dynamic programming problems.

The first problem is the 0/1 Knapsack problem, defined as follows: Given a knapsack with a given weight limit and several items, each having a weight and value, find the __maximum__ value and a combination of items—-using each item at most once—-that has that maximum value without exceeding the weight limit.

The second problem is the Change-Making problem, defined as follows: Given an amount of change and several coin denominations, find the __minimum__ number of coins (and their denominations) that make up the given change.


## Testing

Compile the completed Java file from your Lab 6 directory. Once compiled, you can run the class file as follows.

``` powershell
cd #YOUR_LAB6_DIRECTORY
javac *.java 
# For Testing KnapSack, replace num with whichever input file number you want to test with
java KnapSack knapsack-input-num.txt
# For Testing Change Maker, replace num with whichever input file number you want to test with
java ChangeMaker change-input-num.txt
```

The input for execution and the corresponding expected output can be found in `ExpectedOutputs.txt`.

## Submission

- The only files you can modify are `ChangeMaker.java` and `KnapSack.java`.
- `commit` and `push` the finished code to your GitHub repository. You can check the following [page](https://code.visualstudio.com/docs/sourcecontrol/github) to set up GitHub access directly from VS Code. If you think the commit command hangs in VS Code, it probably asks for a commit message in an open file. You would then need to enter a message and close the file before it can commit to GitHub.
- Submit your Github repository to GradeScope for automatic grading.
  
Note: If you use an IDE, such as NetBeans, Eclipse, or IntelliJ, to develop your programs, make sure they will compile and run on the command line before submitting. This may require some modifications to your program (e.g., removing package information).

[^1]: Contributed by [Alex Zhou](https://github.com/yuz727)
