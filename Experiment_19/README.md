# EXPERIMENT No. 19: Log File Writer

## AIM
- To create a simple log file writer.

## SOURCE CODE
```python
with open("log.txt","a") as f:
    msg=input("Enter log: ")
    f.write(msg+"\n")
```

## OUTPUT
```
Message saved in log file.
```

## RESULT
Program executed successfully.
