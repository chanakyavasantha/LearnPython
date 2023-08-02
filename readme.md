

**range function in python**:
![Screenshot from 2023-08-02 21-01-07](https://github.com/chanakyavasantha/LearnPython/assets/93817654/157b3a8d-3088-43aa-b578-c6722eeba6e6)

![Screenshot from 2023-07-13 14-18-38](https://github.com/chanakyavasantha/LearnPython/assets/93817654/24bc738d-07b0-4bb8-a57a-ae8c4949bdd8)# Learn Python 
# Questions on loops in python:
- counting Number of Digits in a given number
![Screenshot from 2023-07-12 14-02-38](https://github.com/chanakyavasantha/LearnPython/assets/93817654/60fad804-a55e-4ccc-9430-901e9e77e3ab)
![Screenshot from 2023-07-12 14-04-04](https://github.com/chanakyavasantha/LearnPython/assets/93817654/e176ccd1-df98-4363-8805-065f1cff296b)

- Sum of First n even numbers
![Screenshot from 2023-07-12 14-19-59](https://github.com/chanakyavasantha/LearnPython/assets/93817654/12508463-4472-4938-b4a3-751e3a3cb832)
![Screenshot from 2023-07-12 14-21-27](https://github.com/chanakyavasantha/LearnPython/assets/93817654/4939f010-1323-4139-9c28-d44179ecfe34)

- Algorithm for checking whether a given is a prime or not:
![Screenshot from 2023-07-13 14-10-27](https://github.com/chanakyavasantha/LearnPython/assets/93817654/fa943176-c733-4106-a3f9-a9678427fe6f)
![Screenshot from 2023-07-13 14-11-19](https://github.com/chanakyavasantha/LearnPython/assets/93817654/520c8aa3-24e5-405f-b4da-28eb66e215f1)

#### Questions on loops in python:
  - Find Sum of first **n** natural numbers in python
  - Optimized Approach
  ![Screenshot from 2023-07-16 17-09-40](https://github.com/chanakyavasantha/LearnPython/assets/93817654/fba0a3ee-8f29-4d23-bad7-ebe6b21c4a79)
  - Better Alogorithms could solve problems in a optimized approach

#### Functions in python:
![Screenshot from 2023-07-13 14-16-00](https://github.com/chanakyavasantha/LearnPython/assets/93817654/57f0fed5-b2e6-4e87-be51-83fd11a9cdd9)
Function should be defined so that:
- it accepts input
- it gives some ouput
- The input have some specific data type
- The produced will also have some specific data type
![Uploading Screenshot from 2023-07-13 14-18-38.png
- Similiarly we have input data type and out put data type for a function in python
- The output data type is called return type
#### Examples:
- What is the return type for input()?
  - String is the return type of input() function 
  - ![Screenshot from 2023-07-13 14-21-22](https://github.com/chanakyavasantha/LearnPython/assets/93817654/71517e06-2c4c-4546-9136-0a8fdbdd6fb8)
  - ![Screenshot from 2023-07-13 14-26-42](https://github.com/chanakyavasantha/LearnPython/assets/93817654/7ce3d51c-cbfc-4c26-98b8-fda0c1738161)
- Write a function in python that tells whether a given numbers is an even number:
- ![Screenshot from 2023-07-16 17-38-43](https://github.com/chanakyavasantha/LearnPython/assets/93817654/75105a66-2635-4204-952b-c4e75ade3ec0)
- ![Screenshot from 2023-07-16 17-38-06](https://github.com/chanakyavasantha/LearnPython/assets/93817654/35a382e4-a53d-4d57-9189-b0321932bf54)

#### Exercise on Functions:
- Write a fucntion to check , whether a given number is prime.
    - Use both Brute Force Approach, and Optimized Approach
```
## Python Program to check whether a given number is prime using Brute Force Approach
n = int(input()) # taking input from user
flag = 0
for i in range(2,n):
  if n % i == 0:
    flag = 1
    break
if flag == 1:
  print("The given number is not prime")
else:
  print("The gven number is prime")

```
```
## Python Program to check whether a given number is prime using Optimized Approach
import math
n = int(input()) # taking input from user
flag = 0
for i in range(2,int(math.sqrt(n))+1):
  if n % i == 0:
    flag = 1
    break
if flag == 1:
  print("The given number is not prime")
else:
  print("The gven number is prime")

```
- Write a function that takes two integers as parameters and returns their sum.
```
## Python Program to design a function that returns sum
def SUM(a,b):
  return a+b
a = int(input("Enter a: "))
b = int(input("Enter b: "))
c = SUM(a,b)
print(c)
```
- Write a function that takes a list of numbers as input and returns the largest number in the list.
```
## Python Program to design a function that finds maximum in a list
def FindMax(li):
  Max = li[0]
  for i in range(len(li)):
    if li[i] > Max:
      Max = li[i]
  return Max
li = list(map(int,input().split()))
c = FindMax(li)
print(c)
```
- **ONE LINE CODE**
```
li = list(map(int,input().split()))
c = max(li)
print(c)
```
- Implement a function that reverses a given string.
```
def rev(a):
  b = ""
  for i in range(len(a)-1,-1,-1):
    b += a[i]
  return b # b will have reversed string
a = "chanakya"
print(rev(a))
```
```
a = "kushik"
b = a[::-1]
print(b)
```
- Implement a function that takes a list of words and returns a new list with the words sorted in alphabetical order.
- Write a function that removes duplicates from a list








