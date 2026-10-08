# Dynamic Programming Problems

This repository contains solutions to classic **Dynamic Programming (DP)** problems in Java, with short explanations and comments to help understand the logic behind each approach.

## 📖 What is Dynamic Programming?
Dynamic Programming is a technique used to solve problems by:
- Breaking them into smaller subproblems.
- Storing (memoizing) the results of those subproblems.
- Reusing stored results to avoid redundant computations.

This makes DP highly efficient compared to naive recursion, especially for problems with **overlapping subproblems**.

## 🧩 Why DP?
- **Naive recursion** often recomputes the same values many times, leading to exponential time complexity.
- **DP with memoization/tabulation** ensures each subproblem is solved once, reducing complexity to polynomial or linear time.

## ⚡ Example: Fibonacci
- **Naive recursion:** `O(2^n)` time (very slow).
- **DP with memoization:** `O(n)` time, `O(n)` space.
- Each Fibonacci number is computed once and stored in a `dp[]` array.

## 🛠️ Contents
- Fibonacci with memoization
- Climbing Stairs
- House Robber
- Coin Change
- Longest Increasing Subsequence
- Longest Common Subsequence  
*(More problems will be added progressively)*

## 🎯 Goal
This repo is meant as a **learning resource** for anyone starting with DP. Each solution includes:
- Clear code
- Inline comments
- Time and space complexity analysis

---
Happy coding 🚀
