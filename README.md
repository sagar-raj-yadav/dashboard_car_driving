A new Amazon intern encountered a challenging task.

Currently, the intern has n integers, where the value of the th element is represented by the array element values[i]. The intern is curious to play with arrays and subsequences

and thus asks you to join him.

Given n integer, array values, and an integer k, the intern needs to find the maximum and minimum median overall subsequences of length k.

Example:

Given n = 3, values = [1, 2, 3], and k = 2.

Subsequences of length k

median

[1, 2]

[1, 3]

[2,3]

3

Here, the maximum median present is 2 and the minimum median in the subsequence present is 1.

Function Description

Complete the function medians in the editor below.

medians has the following parameter(s):

int values[n]: the value of integers.

int k: the given integer

Returns

int: the maximum and minimum overall subsequences of length k in the form [maximum median, minimum median).
