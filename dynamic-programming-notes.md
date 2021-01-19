---
description: Credits to Aditya Verma
---

# Dynamic Programming Notes

## Ways to identify Dynamic Programming problems

DP is just enhanced recursion, once you write a recursion for the problem it can be easily solved using DP. Generally if a function is making a single recursive call it would not count as a DP problem, however if there are more than one recursive call, then there is a possibility that some of the values may have been pre-computed and therefore one can consider applying DP.

a\) **Element of Choice** : It involves choosing an element or completely excluding it from the solution  
b\) **Optimal** : The problem would involve solving for the maximum, minimum or largest value from a give set of inputs. 

## Steps to solve a DP Problem

a\) As mentioned above first write down the recurrence relation.  
b\) Memoize the solution  
c\) Write down a top down solution to the problem using a matrix or array

