Bubble Sort can be optimized to reduce unnecessary iterations if the array becomes sorted before completing all passes. Write a program to implement an adaptive Bubble Sort that stops early when no swaps are made during a pass. Additionally, count the total number of swaps and passes made during the sorting process.

Input1: N = 5
arr = [64, 34, 25, 12, 22]

Output1: Sorted Array: [12, 22, 25, 34, 64]
Total Swaps: 9
Total Passes: 4

Input2: N = 5
arr = [64, 34, 25, 22, 12]

Output2: Sorted Array: [12, 22, 25, 34, 64]
Total Swaps: 10
Total Passes: 4
