# EXPERIMENT No. 16: File Copy

## AIM
- To copy content from one file to another.

## SOURCE CODE
```python
with open("a.txt") as f1, open("b.txt","w") as f2:
    f2.write(f1.read())
```

## OUTPUT
```
File copied.
```

## RESULT
Program executed successfully.
