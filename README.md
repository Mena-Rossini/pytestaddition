
# Ex.No: 12 Pytest program for Addition

### DATE: 22/10/2024                                                                          
### REGISTER NUMBER : 212222040099
### AIM: 
To write a python program for addition of two numbers and test the test cases using Pytest.
### Algorithm:

1. Write the python program for addition of a number. 
2. Make sure that function name should be “def test_*():” and the line to be tested 
should have assert keyword at the beginning. 
3. Write some test cases for to be tested and save it as “test_add.py”. 
4. Open command prompt and change the directory to where pytest is installed
5. Executethe program as “pytest test_sumofdig.py”. 
6. Stop the program.

### Program:
```
def add(a, b):
    return a + b

def test_3_plus_5_equals_8():
    assert add(3, 5) == 8

def test_2_plus_3_equals_5():
    assert add(2, 3) == 6

```

### Output:

![image](https://github.com/user-attachments/assets/669ece63-e2bd-4828-a307-f3a6f414b119)

### Result:
Thus, the python program for addition of two numbers is tested using pytest and executed and output is verified successfully.
