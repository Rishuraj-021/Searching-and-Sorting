# Searching-and-Sorting
.

# 📌 1. Selection Sort
## 🎯 Aim:
To implement Selection Sort in C++ and understand its working mechanism.

## 📖 Theory:
Selection Sort is a simple comparison-based algorithm. It divides the array into a sorted and an unsorted part.
The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion and swaps it with the first unsorted element, thus growing the sorted part step by step.

Time Complexity: O(n²) (best, average, worst)
Space Complexity: O(1) (in-place sorting)
Sorting Type: Comparison-based, In-place, Not Stable

## ⚙️ Algorithm:
Start with the first element as the minimum.
Compare this element with all other elements to find the smallest.
Swap the smallest element with the first unsorted element.
Move the boundary of the sorted part by one step.
Repeat until the whole array is sorted.

## ✅ Conclusion:
Selection Sort is easy to implement but inefficient for large datasets due to its O(n²) complexity. It is best suited for small arrays where simplicity is preferred over efficiency.

# 📌 2. Insertion Sort
## 🎯 Aim:
To implement Insertion Sort in C++ and analyze its efficiency.

## 📖 Theory:
Insertion Sort builds the sorted array one item at a time by repeatedly picking the next element and inserting it into the correct position among the already sorted elements.

Time Complexity:
Best Case (Already Sorted): O(n)
Average & Worst Case: O(n²)
Space Complexity: O(1)
Sorting Type: Stable, In-place

## ⚙️ Algorithm:
Consider the first element as sorted.
Pick the next element.
Compare it with elements in the sorted portion.
Shift elements greater than the key to the right.
Insert the key into its correct position.
Repeat until all elements are sorted.

## ✅ Conclusion:
Insertion Sort is efficient for small datasets and nearly sorted arrays. It is stable and easy to implement but performs poorly on large datasets due to quadratic time complexity.

# 📌 3. Bubble Sort
## 🎯 Aim:
To implement Bubble Sort in C++ and study its performance.

## 📖 Theory:
Bubble Sort repeatedly swaps adjacent elements if they are in the wrong order. With each pass, the largest element "bubbles up" to the end of the array.

Time Complexity:
Best Case (Already Sorted): O(n) (with optimization)
Average & Worst Case: O(n²)
Space Complexity: O(1)
Sorting Type: Stable, In-place

## ⚙️ Algorithm:
Compare each pair of adjacent elements.
Swap them if they are in the wrong order.
Repeat this process for all elements.
After each pass, the largest element is placed at the end.
Continue until no swaps are needed.

## ✅ Conclusion:
Bubble Sort is simple but highly inefficient for large datasets. It is mainly useful for teaching purposes and understanding sorting concepts, not for real-world applications.

# 📌 4. Linear Search:

## 🎯 Aim:
To implement Linear Search in C++ and understand its basic mechanism for finding an element in a list.

## 📖 Theory:
Linear Search is the simplest searching algorithm. It works by sequentially checking each element of the array or list until the desired element is found or the end of the list is reached. It does not require the data to be sorted and is suitable for small or unsorted datasets.
- Time Complexity:
- Best Case: O(1) (element found at the beginning)
- Worst Case: O(n) (element not found or at the end)
- Average Case: O(n)
- Space Complexity: O(1)
- Search Type: Sequential, Unsorted, Non-optimized
- 
## ⚙️ Algorithm:
- Start from the first element of the array.
- Compare the current element with the target value.
- If it matches, return the index or indicate success.
- If not, move to the next element.
- Repeat steps 2–4 until the end of the array.
- If no match is found, return failure or -1.
- 
## ✅ Conclusion:
Linear Search is easy to implement and works well for small or unsorted datasets. However, it is inefficient for large datasets due to its linear time complexity. For better performance on large or sorted data, algorithms like Binary Search are preferred.

## 📝 Final Notes:
- All four algorithms—Selection Sort, Insertion Sort, Bubble Sort, and Linear Search—are foundational techniques in algorithm design.
- While they are simple and intuitive, they are not optimal for large-scale applications.
- For sorting, prefer Merge Sort or Quick Sort; for searching, Binary Search or Hashing techniques offer better efficiency.
- These basic algorithms are excellent for learning and understanding core programming concepts.
Would you like this compiled into a printable format or expanded with Binary Search next?


