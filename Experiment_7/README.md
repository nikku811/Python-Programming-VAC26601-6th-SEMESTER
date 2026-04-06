# EXPERIMENT No. 7: Fibonacci Series

## AIM
- To generate sequence using loops.

## SOURCE CODE
```python
n = int(input("Enter terms: "))
a, b = 0, 1

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

## OUTPUT
```
Enter terms: 5
0 1 1 2 3
```

## RESULT