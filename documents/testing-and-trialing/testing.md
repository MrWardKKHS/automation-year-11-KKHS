## Test 1 EXAMPLE:
# Getting user input

Date: 1/1/2022

```python
choice = input('please input a number between 1 and 10')
```

| Test Data | Expected | Observed |
| --------- | -------- | -------- |
| 'word'    | please input a number | ValueError
| -4        | invalid number, please pick a number between 1 and 10 | as expected 
8.5         | Please enter a whole number | ValueError |
8           | Program continues with value set to 8 | as expected

