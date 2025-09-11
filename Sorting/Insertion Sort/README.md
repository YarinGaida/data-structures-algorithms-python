# Insertion Sort  

## 📌 Overview  
Insertion Sort is a simple sorting algorithm that builds the sorted array one element 
at a time by repeatedly inserting elements into their correct position.  

## ⏱️ Complexity  
- Best case: O(n) (already sorted input)  
- Average case: O(n²)  
- Worst case: O(n²)  
- Space complexity: O(1)  

## 🔑 Idea  
- Iterate through the array from left to right  
- At each step, insert the current element into its correct position among the previously sorted elements  

## 🧩 Example Usage  
```python
from insertion_sort import insertion_sort  

arr = [5, 2, 4, 6, 1, 3]  
print(insertion_sort(arr))  # [1, 2, 3, 4, 5, 6]

