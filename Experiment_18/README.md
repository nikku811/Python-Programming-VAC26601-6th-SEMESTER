# EXPERIMENT No. 18: Count Lines and Words

## AIM
- To count number of lines and words in a file.

## SOURCE CODE
```python
with open("test.txt") as f:
    data=f.read()

print("Lines:",data.count("\n")+1)
print("Words:",len(data.split()))
```

## OUTPUT
```
Displays line and word count.
```

## RESULT
Program executed successfully.
