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
count = 0
while True:
    print(f"Current count: {count}")
    count += 1
    if count > 5:
        break
```
## 2.while
```
count = 1
while count <= 5:
  print(count)
  count += 1
```
## 3.for
```
num = int(input("Enter a number: "))

for i in range(1, 11):
    print(f"{num} x {i} = {num * i}")

print()
```
## 4.switch
```


day = int(input("Enter day number (1-7): "))

match day:
    case 1:
        print("Monday")
    case 2:
        print("Tuesday")
    case 3:
        print("Wednesday")
    case 4:
        print("Thursday")
    case 5:
        print("Friday")
    case 6:
        print("Saturday")
    case 7:
        print("Sunday")
    case _:
        print("Invalid day number")

print()

```
## 5.if else
```
num = int(input("Enter a number: "))
if num % 2 == 0:
    print(num, "is even")
else:
    print(num, "is odd")

```

## Output

<img width="626" height="160" alt="image" src="https://github.com/user-attachments/assets/91d5e676-b9eb-46f8-befc-7942d1f0d340" />

<img width="586" height="129" alt="image" src="https://github.com/user-attachments/assets/284f4976-0d2e-4210-b288-6e287a2e310c" />

<img width="635" height="277" alt="image" src="https://github.com/user-attachments/assets/6136a859-fbd2-4b73-9344-ae9cc931fc78" />

<img width="631" height="76" alt="image" src="https://github.com/user-attachments/assets/51a7be3e-da95-4dcf-a617-dad8999d8969" />

<img width="599" height="69" alt="image" src="https://github.com/user-attachments/assets/4401eed0-a27f-4e7e-b12b-07f4d5af0efc" />


## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.




