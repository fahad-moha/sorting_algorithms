# Sorting algorithms & Big O

1. Four different sorting algorithms:
   - Bubble Sort: It repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. It continues until the list is sorted.
   - Selection Sort: It divides the input list into a sorted and an unsorted region. It repeatedly finds the minimum element from the unsorted region and swaps it with the first element of the unsorted region.
   - Insertion Sort: It builds the final sorted array one item at a time. It takes each element from the input list and inserts it into its correct position in the sorted array.
   - Merge Sort: It follows the "divide and conquer" approach. It divides the input list into smaller sublists, recursively sorts them, and then merges them to produce a sorted output.

2. Big O notation: Big O notation is used to describe the upper bound or worst-case scenario of the time complexity of an algorithm. It provides a way to analyze and compare the efficiency of algorithms as the input size grows. The notation represents how the algorithm's time or space requirements scale with the input size.

3. Evaluating time complexity: To evaluate the time complexity of an algorithm, you analyze how the execution time grows with respect to the input size. You consider the number of operations performed, such as comparisons, assignments, or iterations, and analyze how they change as the input size increases. The dominant term or the term with the highest impact on the growth rate is used to express the time complexity using Big O notation.

4. Selecting the best sorting algorithm: The choice of the best sorting algorithm depends on various factors, including the characteristics of the input data and the desired performance. Consider the following factors:
   - Input size: Some algorithms perform better with small input sizes, while others excel with large input sizes.
   - Input characteristics: Certain algorithms are better suited for specific input distributions (e.g., partially sorted, nearly sorted, or uniformly distributed).
   - Space complexity: If memory usage is a concern, you may prefer algorithms with lower space complexity.
   - Stability requirement: If you need to maintain the relative order of equal elements, you would choose a stable sorting algorithm.

5. Stable sorting algorithm: A stable sorting algorithm preserves the relative order of elements with equal keys during the sorting process. In other words, if two elements have the same key, the one that appears earlier in the original list will also appear earlier in the sorted list. This property is important when sorting objects with multiple attributes or when the original order of equal elements needs to be maintained. Examples of stable sorting algorithms include Insertion Sort, Merge Sort, and Tim Sort.

# Author
Fahad Moahamed
