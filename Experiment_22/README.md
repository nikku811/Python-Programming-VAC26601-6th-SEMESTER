# EXPERIMENT No. 22: Display Installed Packages

## AIM
- To display all installed Python packages.

## SOURCE CODE
```python
import pkg_resources
for p in pkg_resources.working_set:
    print(p.project_name)
```

## OUTPUT
```
Displays list of installed packages.
```

## RESULT
Program executed successfully.