# Push Swap

## Description
Push Swap is a sorting algorithm that receives a list of integers as argument, and sorts it using two stacks and a set of specific operations. The goal is to sort the list with the minimum possible amount of operations.

## Rules
There are two stacks named A and B. Initially, all integers are on stack A, and stack B is empty. The following operations are allowed:
- **sa**: swap the first two elements of stack A
- **sb**: swap the first two elements of stack B
- **ss**: do sa and sb simultaneously
- **pa**: pop the first element of stack B and push it onto stack A
- **pb**: pop the first element of stack A and push it onto stack B
- **ra**: rotate stack A (shift up all elements by one). The first element becomes the last one
- **rb**: rotate stack B (shift up all elements by one). The first element becomes the last one
- **rr**: do ra and rb simultaneously
- **rra**: reverse rotate stack A (shift down all elements by one). The last element becomes the first one
- **rrb**: reverse rotate stack B (shift down all elements by one). The last element becomes the first one
- **rrr**: do rra and rrb simultaneously
