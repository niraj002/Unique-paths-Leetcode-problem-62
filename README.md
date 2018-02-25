# Unique-paths-Leetcode-problem-62
A robot is located at the top-left corner of a m x n grid (marked 'Start' in the diagram below).  The robot can only move either down or right at any point in time. The robot is trying to reach the bottom-right corner of the grid (marked 'Finish' in the diagram below).  How many possible unique paths are there?
A robot is located at the top-left corner of a m x n grid (marked 'Start' in the diagram below).

The robot can only move either down or right at any point in time. The robot is trying to reach the bottom-right corner of the grid (marked 'Finish' in the diagram below).

How many possible unique paths are there?


If there is a 3 x 7 grid. How many possible unique paths are there?
Note: m and n will be at most 100.

Solution:
The code is a bottom up dp approach which uses a 2D array of the same size as the input. Each cell of the dp array stores the total number of ways in which that cell can be reached. 
In this way when the array is completely populated, the rightmost bottom element will have the value of number of ways of reaching to that point.
The solution runs in quadratic time and it uses quadratic space
