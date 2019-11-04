# Python Programming Language

## Assignmnet : 1
 
### 1. Write a Python program to print the following string in a specific format (see the output).

Twinkle, twinkle, little star,
How I wonder what you are!
Up above the world so high,
Like a diamond in the sky.

Twinkle, twinkle, little star,
How I wonder what you are

#### CODE :
```python
print("Twinkle, twinkle, little star, \n\tHow I wonder what you are! \n\t\tUp above the world so high, \n\t\tLike a diamond in the sky. \nTwinkle, twinkle, little star, \n\tHow I wonder what you are!")
```
#### OUTPUT :
 
![alt text](https://github.com/engineerbaz/Certified-Python-Saylani-/blob/master/assignments/a1.PNG "Q 1")

<hr>

### 2. Write a Python program to get the Python version you are using.

#### CODE :
```python
import sys
print("Python version")
print (sys.version)
print("Version info.")
print (sys.version_info)
```
#### OUTPUT :
>Python version <br>
>3.6.8 (default, Oct  7 2019, 12:59:55) <br>
>[GCC 8.3.0] <br>
>Version info. <br>
>sys.version_info(major=3, minor=6, micro=8, releaselevel='final', serial=0) <br>

<hr>

### 3.Write a Python program to display the current date and time.

#### CODE :
```python
import datetime
now = datetime.datetime.now()
print ("Current date and time : ")
print (now.strftime("%Y-%m-%d %H:%M:%S"))
```
#### OUTPUT :
> Current date and time : <br>
> 2019-11-04 09:38:21


<hr>

### 4. Write a Python program which accepts the radius of a circle from the user and compute the area.

#### CODE :
```python
from math import pi
r = float(input ("Input the radius of the circle : "))
print ("The area of the circle with radius " + str(r) + " is: " + str(pi * r**2))
```
#### OUTPUT :
> Input the radius of the circle : 10 <br>
> The area of the circle with radius 10.0 is: 314.1592653589793

<hr>

### 5. Write a Python program which accepts the user's first and last name and print them in reverse order with a space between them.

#### CODE :
```python
fn = input("Input your First Name : ")
ln = input("Input your Last Name : ")
print ("Hello  " + ln + " " + fn)
```
#### OUTPUT :
> Input your First Name : Ali <br>
> Input your Last Name : Farooq <br>
> Hello  Farooq Ali

<hr>

### 6. Write a python program which takes two inputs from user and print them
addition

#### CODE :
```python
val1 = int(input("Input a number : "))
val2 = int(input("Input another number : "))
add = val1 + val2 
print('List : ',add) 
```
#### OUTPUT :
> Input a number : 2 <br>
> Input another number : 44 <br>
> List :  46 <br>

<hr>
