# Lecture Notes 3
### Date: 10-May-2020

* Python is indentation sensitive language.
* `:` symbol is used to denote the sub-body or internal body
* Misplacement in python code due to indentation results in compile error.

__If Else__
* It is conditional statement used for checking conditions and execution part which satisfies it.
* Syntax:
  ```
    if(condition 1):
        body of if
    elif(condition 2):
        body of elif
    else:
        body of else
  ```      
* For Example:
  ```
  x = int(input())
  if(x > 10):
      print("The number is greater than 10")
  elif(x < 10):
      print("The number is less than 10")
  else:
      print("Equal")
  ```
__Loops__
* It helps in executing iterative statements based on conditions till they are satisfied.
* There are 3 types of loops:
  * For Loop
  * While Loop
  * Do While Loop
* For Example:
```
  x = int(input())
  while(x > 10):
      print("Hello")
```
* when condition is satisified all time than programs runs into infinite loop.
* Infinite Loop - No blocking condition and loop keeps on executing the code inside it.
* __CTRL + Z__ - Stops the infinite loop during exection.
```
  x = int(input())
  while(x > 10):
      print("Hello")
      x = x - 1
```
* `break` is a selection statement that brings control out of the loop anytime. 
* To use inbuilt functions, Python uses support of libraries which contains the pre-defined methods.
* __import__ is used to import the library and is always defined on top of program code.
* For Example:
  * `import random` - Here, random is the name of the python library <br>
  * `randint(a, b)` - randint() method takes two arguements which generates the random numbers between them
* To use a method of another function, `.`(dot) operator is used 
  * Syntax: `libraryName.methodName` 
  * For Example: 
  ```
  import random
  r = random.randint(1, 20)
  ```
* Program 4 : [Program for Number Guessing Game](https://github.com/abhinavg916/ytcodehelp-python/blob/master/Lectures/Lecture3/4NumberGuessingGame.py)
* boolean values are represented in capital form otherwise compile time error.
  ```
  while(True):
  ```



  