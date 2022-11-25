# Python - Getting Started

- # uses of python :thinking: ?
    - Automation
    - Science
    - Desktop
    - Android
    - Web
    - Machine Learning

- # Types in Python?
- No need to Explicitly Declare data types.
- But this can lead to errors i.e adding a number with a string!
- we can use ***type hinting*** but can have errors in run time. 
- ``` def add_numbers(a:int , b:int ) :```
- ## integer and floats
    - ``` age = 20 #integer (numbers i.e +ve, -ve, 0, no decimal numbers```
    - ``` bank_balance = 0.5 # float (decimal numbers) ```
    - #### type casting
    - ```int(5.4) = 5  # float to int conversion```
    - ```float(5) = 5.0  # int to float conversion```
- ## strings
    - ``` username = "md" == 'md' == """md""" # string ``` 
    - ***three times quote string*** is used for function docs
    - it can't be assidned to variable..it is just printed
    - #### String methods
    - ```"name".capitalize() == "Name"```
    - ```"name".replace("a","e") == "Neme"```
    - ```"name".isalpha() == True```
    - ```"123".isdigit() == True```
    - ```"some, all, new , old".split(",") == ["some","all","new","old"]```
    - ###### String Format function
        - ```name="some"```
        - ```machine="robot"```
        - ```"Nice to meet you {0}. i'm a {1}".format(name, machine)```
        - ```***#output***```
        - ```Nice to meet you some. i'm a robot```
    - ###### String interpolation
        - ```f"Nice to meet you {name}. i'm a {machine}"```
        - ```#***output***```
        - ``` Nice to meet you some. i'm a robot```
    - ###### Raw String
        - ```r"Nice to meet you {name}. i'm a {machine}"```
        - ```#***output***```
        - ``` Nice to meet you some. i'm a robot```
    - ###### unicode String
        - ```u"Nice to meet you {name}. i'm a {machine}"```
        - ```#***output***```
        - ``` Nice to meet you some. i'm a robot```

- ## Boolean and None
    - Boolean have two values like True or False
    - ``` python_Course = True ```
    - ``` java_Course = False ```
    - #### Boolean conversion
        - ```int(True) == 1```
        - ```int(False) == 0```
        - ```str(False) == "False"```
    - None means variable declared but assigned none
    - ```kt=None```

- # Conditional statements in python :thinking: ?
There are ***if statements, not-if statements, Ternary if statements, if-else statements, else-if or elif statements*** in python.
- ## if statement
    - The code under if statement will execute only if the condition true.
    - ``` variable_name == 5```
    - ``` if variable_name == 5 :```
    - ```   print("This will execute")```
    - #### Truthy statements
    - means if variable have value and it is not 0 or False
    - ***using number***  
    - ``` variable_name == 5```
    - ``` if variable_name :```
    - ```   print("This will execute")```
    - *** using string ***
    -  ``` variable_name == "value"```
    - ``` if variable_name :```
    - ```   print("This will execute")```
    - *** using Boolean ***
    -  ``` variable_name == True```
    - ``` if variable_name :```
    - ```   print("This will execute")```
    - #### Falsy statements
    - means if variable have no value or it have None, 0 or False
    - ***using number***  
    - ``` variable_name == 0```
    - ``` if variable_name :```
    - ```   print("This will not execute")```
    - *** using None ***
    -  ``` variable_name == None```
    - ``` if variable_name :```
    - ```   print("This will not execute")```
    - *** using Boolean ***
    -  ``` variable_name == False```
    - ``` if variable_name :```
    - ```   print("This will not execute")```
    - #### Multiple if conditions
    - ***using OR***
    - means if atleast one of two conditions is true  
    - ``` variable_name1 == 0```
    - ``` variable_name2 == 1```
    - ``` if variable_name1==0 OR variable_name2==2 :```
    - ```   print("This will  execute")```
    - ***using AND***
    - means if all  conditions are true  
    - ``` variable_name1 == 0```
    - ``` variable_name2 == 1```
    - ``` if variable_name1==0 AND variable_name2==1 :```
    - ```   print("This will execute execute")```
- ## not if statement
    - The code under if statement will execute only if the condition true after applying not operation.
    - ``` variable_name == 5```
    - ``` if variable_name != 5 :```
    - ```   print("This will not execute")```
    - *** using Boolean ***
    -  ``` variable_name == True```
    - ``` if not variable_name :```
    - ```   print("This will not execute")```
- ## if-else statement
    - one if statement, one else statement
    - ``` a == 5```
    - ``` if a == 1:```
    - ```   print("it is one")```
    - ``` else:```
    - ```   print("it is not one")```
- ## ternary if statement
    - The code outputs something if it is true and something else if it is false
    - ``` a == 5```
    - ``` b == 10```
    - ``` "bigger" if a>b else "smaller"```
    - this will output ***smaller***

- ## else-if or elif statements
    - one if statement, one or more else-if or elif statements and a else statement at the end
    - ``` a == 5```
    - ``` if a == 1:```
    - ```   print("it is one")```
    - ``` elif a == 2:```
    - ```   print("it is two")```
    - ``` elif a == 3:```
    - ```   print("it is three")```
    - ``` elif a == 4:```
    - ```   print("it is four")```
    - ``` elif a == 5:```
    - ```   print("it is five")```
    - ``` else:```
    - ```   print("it is not in between 1-5")```

- # Lists in python :thinking: ?
multiple values in one variable i.e arrays in other languages are lists in python.

- ## Create lists
    - #### empty list
    - ``` students = []```
    - #### list with values
    - ``` students = ["name1", "name2","name3"]```
- ## access list elements
    - #### first element
    - ``` students[0]```
    - #### last element
    - ``` students[-1]```
    - #### any specific element i.e 3rd element
    - ``` students[2]```
- ## changing list element value
    - ``` students[0]=name1new```
- ## list with value of different types
    - ``` random = ["name","number","bool"]```
- ## list functions
    - #### add new element to list at the end
    - ```students.append("name4")```
    - #### check if specific value is in list
    - ```"name4" in "students"```
    - #### check length of list
    - ``` len(students)```
    - #### delete element from list
    - ``` students[2] ```
    - #### list slicing
        - #### skip first element and print other
        - ``` student[1:]```
        - #### skip first and last element and print rest
        - ``` student[1:-1]```

- # Loops in python :thinking: ?
execute some instructions for multiple times based on some conditions

- ## for loop in python :thinking: ?
    - #### for loop for lists
    - ``` students = ["a","b","c","d","e","f"]```
    - ``` for student in students: ```
    - ```   print(f"{student}") ```
    - #### for loop for specific iterations
    - ``` x=0```
    - ``` for index in range(10): ```
    - ```   print(f"{x}") ```
    - #### for loop for start and end value
    - ``` x=0```
    - ``` for index in range(5,10): ```
    - ```   print(f"{x}") ```
    - #### for loop for start, end value with increment value
    - ``` x=0```
    - ``` for index in range(5,10,2): ```
    - ```   print(f"{x}") ```
    - #### Break in loops
    - ``` break will exit loop suddenly```
    - ``` students=["a","b","c","d","e","f"]```
    - ``` for student in students: ```
    - ```   if student == "d": ```
    - ```       print(f"{student}") ```
    - ```       break```
    - ```   print("Testing...") ```
    - #### continue in loops
    - ``` continue will skip current iteration```
    - ``` students=["a","b","c","d","e","f"]```
    - ``` for student in students: ```
    - ```   if student == "d": ```
    - ```       continue```
    - ```       print(f"{student}") ```
    - ```   print(f"Testing...{student}") ```


- ## while loop in python :thinking: ?
    - ``` x=0```
    - ``` while x > 10: ```
    - ```   print(f"count is {x}") ```
    - ```   x +=1```
    - #### ifinite loop
    - ``` x=0```
    - ``` while True: ```
    - ```   print(f"{x}") ```

- # Dictionaries in python :thinking:?
Dictionaries in python are a group of key value pairs. same as json or objects in javascript
- ## create dictionary in python
    - #### single dictionary
    ``` student = {```
    ```    "name" : "john",```
    ```    "rollno" : 1234,```
    ```    "feedback" : None```
    ```}```
    - #### list of dictionary
    ``` students = [```
    ``` {"name" : "john1","rollno1" : 1234,"feedback1" : None}```
    ``` {"name" : "john2","rollno2" : 1235,"feedback2" : None}```
    ``` {"name" : "john3","rollno3" : 1236,"feedback3" : None}```
    ``` {"name" : "john4","rollno4" : 1237,"feedback4" : None}```
    ```]```
- ## access dictionary values in python
    - #### access value in single dictionary
    - ``` print(f"{student["name"]}")```
    - #### access value in list of dictionaries
    - ``` for student in students:```
    - ```   print(f"{student["name"]}"```
    - #### what if we access a key that does not exist?
    - ``` print(f"{student["lastname"]}")  #this brings ky error```
        - ###### how to avoid?
        - ```student.get("lastname","unknown")```
        - this will print unknown as lastname is not fonud
    - #### how to get all keys?
    - ```student.keys()```
    - #### how to get all values?
    - ```student.values()```
- ## chnaging or deleting values
    - #### changing values
    - ``` student["name"] = "newname"```
    - #### deleting values
    - ``` del student["name"] ```

- # Exceptions in python :thinking:?
An exception is an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions.
- ## try and except in python 
    -   to avoid exceptions , we  use try and except
    - #### try and except : example
    -``` student = {```
    ```    "name" = "somename",```
    ```    "rollno" = 1234,```
    ```    "feedback" = None```
    ```}```
    ``` student["lastname"]="somelastname"```
    ``` try:```
    ```     lastname=student[lastname]  ```
    ```     somenumber = 3 + student["lastname"]```
    ``` except KeyError:```
    ```     print("error finding lastname")``` 
    ``` except TypeError as error:```
    ```     print("i can't add these two togather")```
    ```     print(error) ```
    ``` except Exception:```
    ```     print("unkown Error")``` 