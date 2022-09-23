
arr = [3, 2, 1, 4]

arr[::2] = sorted(arr[::2])
arr[::2], arr[1::2] = sorted(arr[::2]), sorted(arr[1::2])
print(arr)
