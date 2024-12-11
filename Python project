# Bubble Sort
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]

# Selection Sort
def selection_sort(arr):
    n = len(arr)
    for i in range(n):
        min_idx = i
        for j in range(i+1, n):
            if arr[j] < arr[min_idx]:
                min_idx = j
        arr[i], arr[min_idx] = arr[min_idx], arr[i]

# Insertion Sort
def insertion_sort(arr):
    for i in range(1, len(arr)):
        key = arr[i]
        j = i-1
        while j >= 0 and key < arr[j]:
            arr[j + 1] = arr[j]
            j -= 1
        arr[j + 1] = key

# Example usage:
arr = [64, 34, 25, 12, 22, 11, 90]

# Bubble Sort
bubble_arr = arr.copy()
bubble_sort(bubble_arr)
print("Bubble Sort:", bubble_arr)

# Selection Sort
selection_arr = arr.copy()
selection_sort(selection_arr)
print("Selection Sort:", selection_arr)

# Insertion Sort
insertion_arr = arr.copy()
insertion_sort(insertion_arr)
print("Insertion Sort:", insertion_arr)


