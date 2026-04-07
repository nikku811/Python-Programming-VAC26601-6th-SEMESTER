# EXPERIMENT No. 17: Division Exception Handling

## AIM
- To demonstrate division by zero handling.

## SOURCE CODE
```python
try:
    a=int(input())
    b=int(input())
    print(a/b)
except ZeroDivisionError:
    print("Cannot divide by zero")
```

## OUTPUT
```
Error handled if zero entered.
```

## RESULT
Program executed successfully.
