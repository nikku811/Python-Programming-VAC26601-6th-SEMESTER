# EXPERIMENT No. 9: Simple & Compound Interest

## AIM
- To calculate Simple Interest and Compound Interest.

## SOURCE CODE
```python
p=float(input("Principal: "))
r=float(input("Rate: "))
t=float(input("Time: "))
si=(p*r*t)/100
ci=p*((1+r/100)**t)-p
print("SI:",si)
print("CI:",ci)
```

## OUTPUT
```
Displays SI and CI.
```

## RESULT
Program executed successfully.
