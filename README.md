# DSA using ABAP:
## Missing Number In Array:
Given an array of size n-1 such that it only contains distinct integers in the range of 1 to n. Return the missing element.
>Using sum of N natural numbers

The formula to calculate the sum of N natural numbers = (n*(n+1)) / 2

Just  calculate the sum of n numbers and subtract all the numbers of array from the sum. Remaining will be the missing number.

Code:
```

```

## Duplicates in Array
Find all the duplicate numbers in an array given-  
array of size n and elements in range 0 - (n-1).

>Using secondary array of size n.

1. Create an new array of size n (index will be from 0 to n-1).
2. Every element in the given array will be index for new array and for every occurence increment the index of new array by one.
3. Loop at new array and check for all elements greater than 1.

Example:  
```
Given array [0,2,2,3] n=4  
New array [0,0,0,0]  
First Element  1: New Array [1,0,0,0]  
Second Element 2: New Array [1,0,1,0]  
Third Element  2: New Array [1,0,2,0]  
Fourth Element 3: New Array [1,0,2,1]
```
Code:
```

```

