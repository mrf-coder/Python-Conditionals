# Python-Conditionals

```
Conditional definition in Python refers to control flow statements that allow code execution to
depend on whether certain conditions are met. The primary conditional statements in Python are if, elif(else if),
 and else.These statements enable a program to make decisions and execute
different blocks of code based on the truthiness of specified conditions. 
if statement:
This statement executes a block of code only if the specified condition evaluates to True.
elif statement:
This statement allows checking multiple conditions in sequence. It is used after an if statement
and executes its block of code only if the preceding if or elif conditions are False and its own condition is True.
else statement:
This statement provides a default block of code to execute if none of the preceding if or elif conditions are True.
### Python Conditions and If statements
Python supports the usual logical conditions from mathematics:
+ Equals: a == b
+ Not Equals: a != b
+ Less than: a < b
+ Less than or equal to: a <= b
+ Greater than: a > b
+ Greater than or equal to: a >= b

These conditions can be used in several ways, most commonly in "if statements" and loops.

```
```js
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y:
    print("x is less than y")
if x > y:
    print("x is greater than y")
if x == y:
    print("x is equal to y")
Check all the statements one by one
```
```js
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y:
    print("x is less than y")
elif x > y:
    print("x is greater than y")
else x == y:
    print("x is equal to y")
it stoped when the condition is find not checking other conditions
```
```js
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y or x>y:
    print("x is not equal to y")
else:
    print("x is equal to y")    

if x<y or x>y any one of condition is true then print x is not equal to y  stop
if x<y or x>y no one true condition then print x is equal to y  stop
```
```js
x = int(input("What's x? "))
y = int(input("What's y? "))

if x != y:
    print("x is not equal to y")
else:
    print("x is equal to y")    


if x != y  condition is true  print x is not equal to y  stop
else print x is equal to y  stop
```

