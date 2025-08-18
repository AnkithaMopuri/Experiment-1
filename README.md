# Experiment-1
# Name:Mopuri Ankitha
# Register Number:212223040117
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
## 1.do while
```
def do_while_example(start):
    result = []
    while True:
        result.append(start)
        start += 1
        if start > 5:
            break
    return result
def test_1():
    assert do_while_example(2) == [2, 3, 4, 5]
def test_2():
    assert do_while_example(2) == [2, 3, 4]

```
## 2.while
```
def while_loop_example(start):
    result = []
    while start < 5:
        result.append(start)
        start += 1
    return result

def test_while_loop_1():
    assert while_loop_example(2) == [2, 3, 4]

def test_while_loop_2():
    assert while_loop_example(2) == [2, 3]


```
## 3.for
```
def for_loop_example(start):
    result = []
    for i in range(start, 5):
        result.append(i)
    return result

def test_for_loop_1():
    assert for_loop_example(2) == [2, 3, 4]

def test_for_loop_2():
    assert for_loop_example(2) == [2, 3]


```
## 4.switch
```
def switch_example(value):
    match value:
        case 1:
            return "One"
        case 2:
            return "Two"
        case _:
            return "Other"

def test_switch_1():
    assert switch_example(1) == "One"
    assert switch_example(2) == "Two"
    assert switch_example(5) == "Other"

def test_switch_2():
    assert switch_example(1) == "Two"




```
## 5.if else
```
def if_else_example(num):
    if num > 5:
        return "Greater"
    else:
        return "Smaller or equal"

def test_if_else_1():
    assert if_else_example(7) == "Greater"
    

def test_if_else_2():
    assert if_else_example(7) == "Smaller or equal"



```

## Output
## do while:
<img width="1266" height="416" alt="dowhileoutput" src="https://github.com/user-attachments/assets/29047b74-4c41-46b8-b8cc-f02cb11b3bd5" />

## while:
<img width="1279" height="448" alt="while" src="https://github.com/user-attachments/assets/e40d67ad-d118-4d27-b544-f436bc229ea1" />

## for:
<img width="1279" height="420" alt="for" src="https://github.com/user-attachments/assets/eba896f6-f80b-4bdc-8407-874addf09bda" />

## switch:
<img width="1279" height="420" alt="switch" src="https://github.com/user-attachments/assets/46d585ac-2228-4b49-893e-d3d37b4f0e6b" />

## if-else:
<img width="1279" height="420" alt="ifelse" src="https://github.com/user-attachments/assets/bc1d297a-cc62-46d1-8a2e-1eb3c1fd81df" />



## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.




