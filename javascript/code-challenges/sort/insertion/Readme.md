# Insertion code

## Psuedo Code

![psuedo](/javascript/code-challenges/sort/insertion/Screenshot%202023-05-08%20at%208.04.47%20PM.png)

## BigO

Insertion sort has a worst-case TIME complexity of O(n^2), which occurs when the input array is reverse ordered. In this scenario, the algorithm must compare each element with all the other elements that come before it, resulting in n(n-1)/2 comparisons. However, when the input array is already sorted or nearly sorted, the time complexity can improve to O(n).

The SPACE complexity of insertion sort is O(n), which means that the maximum amount of extra space required by the algorithm is linearly proportional to the size of the input array. Specifically, the algorithm requires space for two arrays: the input array and a temporary array used to store elements during the sorting process.


## Step Through

![ccinsert](/javascript/code-challenges/sort/insertion/1.png)
