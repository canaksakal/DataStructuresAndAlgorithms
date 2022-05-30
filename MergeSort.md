# **Merge Sort Work**
> ## [16,21,11,8,12,22] -> Merge Sort
> 1. Write the stages of the above array according to the sort type.
> 2. Write the Big-O notation.
---
**Answers**
---
1)  - [16,21,11,8,12,22]
    - [16,21,11] - [8,12,22]
    - [16] - [21,11] - [8] - [12,22]
    - [16] - [21] - [11] - [8] - [12] - [22]
    - [16,21] - [8,11] - [12,22]
    - [8,11,16,21] - [12,22]
    - [8,11,12,16,21,22]
---
2) There are 6 steps so n=6, O(n*(logn)) -> O(6*(log6))
---