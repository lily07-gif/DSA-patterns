# DSA-patterns
Important DSA patterns to cover

1. Prefix sum:
   It involves preprocessing an array to create a new array where each element at index i represent the sum of the array from the start up to i.
   This allows for efficient sum queries on subarrays.
   Formula : p[i]-p[i-1]+arr[i]

   Preprocess means the process of converting raw, messy data into a clean, structured, and usable format that is suitable for analysis or building machine learning models.

   Example :
    nums=[1,2,3,4,5,6] ; i=1 ; j=3
    output=9
   Explanation:
    Preprocess the array A to create a prefix sum array: p=[1,3,6,10,15,21].
    To find the sum between indices i and j use the above formula.
   How do to the preproocess of an array A?
   You need the put the first element in the array as it is then add the first element with the next element thats your next element for your preprocessing arrayy and it goes on until you complete the array A.
   Its like calculating the cumulating sum
   For the above example: num=[1,2,3,4,5,6] = [1,3,6,10,15,21].
   Now by applaying the formula you get the output of 9.
