# Psuedo Code
```
MergeSort(arr[], l,  r)
If r > l:
     # Find the middle point to divide the array into two halves:  
     middle m = (l+r)/2


# Call mergeSort for first half:   
     Call mergeSort(arr, l, m)


# Call mergeSort for second half:
     Call mergeSort(arr, m+1, r)


# Merge the two halves sorted in step 2 and 3:
     Call merge(arr, l, m, r)
