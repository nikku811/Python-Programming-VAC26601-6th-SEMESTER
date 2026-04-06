# EXPERIMENT No. 8: Prime Number Check

## AIM
- To check whether a number is prime or not.

## SOURCE CODE
```python
num=int(input("Enter number: "))
if num>1:
    for i in range(2,num):
        if num%i==0:
            print("Not Prime")
            break
    else:
        print("Prime")
else:
    print("Not Prime")
```

## OUTPUT
```
Displays whether number is prime.
```

## RESULT
Program executed successfully.
