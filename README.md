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
```js
x = int(input("What's x? "))
y = int(input("What's y? "))

if x == y:
    print("x is  equal to y")
else:
    print("x is not equal to y")    


if x == y  condition is true  print x is  equal to y  stop
else print x is not equal to y  stop
```
```js
#### The or keyword is a logical operator, and is used to combine conditional statements:
score = int(input("Score: "))

if score >= 90 and score <= 100:
 print("Grade: A")
elif score >= 80 and score < 90:
 print("Grade: B")
elif score >= 70 and score < 80:
    print("Grade: C")
elif score >= 60 and score < 70:
    print("Grade: D")
else:
    print("Grade: F")

```
```js
score = int(input("Score: "))

if score >= 90 :
 print("Grade: A")
elif score >= 80 :
 print("Grade: B")
elif score >= 70 :
    print("Grade: C")
elif score >= 60 :
    print("Grade: D")
else:
    print("Grade: F")

```
```js
score = int(input("Score: "))

if 90 <= score <=100 :
 print("Grade: A")
elif 80 <= score <90 :
 print("Grade: B")
elif 70 <= score <80 :
    print("Grade: C")
elif 60 <= score <70 :
    print("Grade: D")
else:
    print("Grade: F")

```
```js
##### Use of % operator
x = int(input("What,s x?"))
if x % 2 == 0:
 print("Even")
else:
    print("Odd")   
```
```js
def main():
    x = int(input("What's x? "))
    if is_even(x):
        print("Even")
    else:
        print("Odd")

def is_even(n):
    if n % 2 == 0:
        return True
    else:
        return False

main()
Depend upon condition of function return true or faulse
```

```js
def main():
    x = int(input("What's x? "))
    if is_even(x):
        print("Even")
    else:
        print("Odd")

def is_even(n):
     return True if n % 2 == 0 else False
       
    

main()

```


```js
  short form
def main():
    x = int(input("What's x? "))
    if is_even(x):
        print("Even")
    else:
        print("Odd")

def is_even(n):
     return  n % 2 == 0 
       
    

main()

```

```js
    ###### USE of Match Statment
name = input("What,s your name ?")
match name :
    case "Harry":
        print("Gryffindor")
    case "Ali":
        print("Gryffindor")
    case "Gry":
        print("Gryffindor")
    case "Doe":
        print("Gryffindor")
    case _:
        print("Who")    
    

```
```js
    Simple Form of MATCH
  name = input("What,s your name ?")
match name :
    case "Harry" | "Ali" | "Gry" | "Doe":
        print("Gryffindor")
   
    case _:
        print("Who")    
```



