# Practical 1: Sorting Algorithms

This practical implements Selection Sort, Bubble Sort, and Merge Sort, insertion sort, quick sort 
Each algorithm includes implementation, time complexity analysis (best, worst, and average cases), and execution time measurement.

# Practical 2: Linear Search

This practical implements the Linear Search algorithm with interactive user input.
It demonstrates:
- Implementation of linear search that returns the index of the target (or -1 if not found).
- Measurement of execution time using `time.perf_counter()`.
- Time complexity analysis (Best, Average, Worst cases).

Usage:
- Interactive: run the script and follow prompts to provide the list and target value.
- Demo: run the script with a demo flag (if provided in the script).
1. linear search 
2. binary search 

# PRACTICAL 3 : Min-Heap and Max-Heap Sort
Description:

This project implements Heap Sort in Python using heapq.

Min-Heap: Sorts elements in ascending order.
Max-Heap: Sorts elements in descending order.
Features
Takes user input for array elements.
Uses heapq.heapify() and heapq.heappop().
Measures execution time using time.perf_counter().
Displays time complexity.
Example

Min-Heap:

Input: 25, 14, 36, 85, 96
Output: [14, 25, 36, 85, 96]

Max-Heap:

Input: 25, 78, 89, 45, 56, 33
Output: [89, 78, 56, 45, 33, 25]
Complexity
Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)
Space Complexity: O(n)
Requirements
Python 3
heapq and time modules (built-in)
Conclusion

The program demonstrates how Min-Heap and Max-Heap can be used to efficiently sort an array in ascending and descending order.

SUMMARY OF PRACT-4:

In this practical, we learned how to find the factorial of a number using two different methods: iterative and recursive. In the iterative method, we use a loop to multiply the numbers from 1 to the given number. In the recursive method, the function calls itself with a smaller value until it reaches the base condition. Both methods give the same factorial result, but they work in different ways.

CONCLUSION:

From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods are useful for calculating factorials, and this practical helped us understand how loops and recursion can be used to solve the same problem.

# PRACTICAL 7:Coin Change Problem Using Dynamic Programming

This project provides a Python solution to the Coin Change Problem using Dynamic Programming. The program determines the minimum number of coins required to make a given target amount from a set of available coin denominations.

The algorithm builds a dynamic programming table to store the minimum coins needed for every amount from 0 to the target value. By reusing previously computed results, it efficiently finds the optimal solution and avoids redundant calculations.

If the target amount can be formed, the program returns the minimum number of coins required. Otherwise, it returns -1 to indicate that no valid combination exists.

Features Efficient Dynamic Programming approach Finds the minimum number of coins required Handles impossible cases by returning -1 Simple and easy-to-understand Python implementation Complexity Time Complexity: O(n × amount) Space Complexity: O(amount) This project is useful for learning Dynamic Programming concepts, practicing algorithm design, and preparing for coding interviews.

summary of PRACT-5:

Summary:
The Knapsack Problem was implemented using Dynamic Programming to find the maximum value within a given weight capacity. DP stores solutions to smaller subproblems and uses them to build the final optimal solution.

Conclusion:
Dynamic Programming provides an efficient and optimal solution to the Knapsack Problem, reducing repeated calculations and improving performance compared with the recursive approach.
