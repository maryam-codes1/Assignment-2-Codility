Assignment 2 – Codility Algorithm Problems in Python

This repository contains my Python solutions and handwritten pseudocode for five problems from the Codility programming lessons. Three are easier problems based on sorting, and two are advanced problems that use the caterpillar method and binary search.

Problem 1: Distinct
This problem counts how many different values appear in an array. The array is sorted so that equal values sit next to each other, and then the different values are counted in a single pass.

Problem 2: MaxProductOfThree
This problem finds the largest product of any three numbers in an array. After sorting, the answer is either the product of the three largest numbers or the product of the two smallest numbers and the largest one, since two negative numbers multiply to a positive.

Problem 3: Triangle
This problem checks whether any three numbers can be the sides of a triangle. After sorting, it is enough to check neighbouring numbers to find a valid triangle.

Problem 4: CountTriangles
This problem counts how many groups of three numbers can form a triangle. It fixes the largest side and moves two pointers towards each other, which allows many triangles to be counted at once.

Problem 5: NailingPlanks
This problem finds the smallest number of nails, used in order, that are needed to nail every plank. It uses binary search to find this number and prefix sums to quickly check whether each plank has a nail.

Files
Assignment_2.ipynb contains the Python code and test results for all five problems. The images contain my handwritten pseudocode.
