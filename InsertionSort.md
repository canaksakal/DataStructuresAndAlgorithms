# **Insertion Sort Work**

> ## [22,27,16,2,18,6] -> Insertion Sort
> 1. Write the stages of the above given array according to the sort type.
> 2. Write the Big-O notation.
> 3. Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the arrays.
> 4. What case does the number 18 fall into after the array is sorted?
---
### **Answers**
1)  - [22,27,16,2,18,6] *// swap 2 and 22* 
    - [2,27,16,22,18,6] *// swap 6 and 27* 
    - [2,6,16,22,18,27] *// 16 is smallest already so stay*
    - [2,6,16,22,18,27] *// swap 18 and 22* 
    - [2,6,16,18,22,27] 
---
2)  - (n*(n+1))/2   ->  O(n^2)
---
3)  - Avarage Case: O(n'2)
    - Worst Case: O(n'2)
    - Best Case: O(n)
---
4)  - It will be avarage case because 18 is in the middle of the array.
---

> ## [7,3,5,8,2,9,4,15,6] 
> 1. Write the first 4 steps of given array.
---
### **Answers**
1)  - [7,3,5,8,2,9,4,15,6]
    - [2,3,5,8,7,9,4,15,6] // Step1
    - [2,3,5,8,7,9,4,15,6] // Step2
    - [2,3,4,8,7,9,5,15,6] // Step3
    - [2,3,4,5,7,9,8,15,6] // Step4
---