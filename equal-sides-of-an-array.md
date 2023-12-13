# [Equal Sides Of An Array](https://www.codewars.com/kata/5679aa472b8f57fb8c000047/python)

## 6 kyu

## First Attempt:
```python
def find_even_index(arr):
    for i in range(len(arr)):
        if sum(arr[:i]) == sum(arr[(i + 1):]):
            return i
    return -1
```

## Revised Attempt
```python
def find_even_index(arr):
  for i in range(len(arr)):
    if sum(arr[:i]) == sum(arr[i+1:]):
            return i
  return -1
```
