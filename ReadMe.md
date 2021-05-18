# python

## python installation 3.7 or above

### Pycharm set up 

#### Documentation with readme.md to store on GIT-HUB

##### dynamically type language

- testing the python env 'print("text")'
- Python is being used worldwide for websites and applications such as LinkedIn
- It is needed in DevSecOps because it is required for the consualtant to have an understanding of the code
- Need to understand the code to add security aspects


- What are variables?
    - Variables work as a placeholder to store data 
      
- String
    - Anything between "" is considered a string

- Boolean 
    - True or false value

- Integers, Float
    - Any Number that is given
  

```python
#Create a varible for first name, last name and DOB
#Syntax name of the varoble = va;ue to store in teh variable
# Naming convention to follow

first_name = "Tyree"
last_name =  "Blake-Bailey"
DOB = 111

print(first_name + " " + last_name)
```

```python
#Create a varible for first name, last name and DOB
#Syntax name of the varoble = va;ue to store in teh variable
# Naming convention to follow

first_name = "Tyree"
last_name =  "Blake-Bailey"
date_birth = 111

print(first_name + " " + last_name)
print(date_birth)

#to find out the type of variable we have method called type()
# taking input from teh user - input()
name = input("Please enter name ")
print("Hello " + name)
```

## Operators 


## Arithmetic Operators| Operand | Description | Example |

|:---------: |:----------------------------: |:--------: |

| + | add two operands (variables) together| X + y + 2 |

| - | subtract two operands (variables) | X - y - 2 |

| * | multiply two operands (variables) | X - y - 2 |

| / | divide two operands (variables) | X - y - 2 |

| % | Modulus - remainder of the division of left operand by the right | X - y - 2 |

| + | add two operands (variables) together| X + y + 2 |## Comparison Operators| Operand | Description | Example |

|:---------: |:----------------------------: |:--------: |


| > | True if left operand is greater than the right| x > y |

| < | True if left operand is less than the right| x < y |

| == | True if both operands are equal | x == y |

| != | True if both operands are equal | x != y |

| >= | True if left operand is greater than or equal to the right| x >= y |

| <= | True if left operand is less than or equal to the right| x <= y  |
 ```python
value1 = 6
value2 = 7

print(value2 > value1) #Greater than
print(value1 < value2) #Less than 
print(value1 + value2) # Addition
print(value2 - value1) #Subtraction
print(value1 >= value2) # Greater than or equal to
print(value1 != value2) # Not equal to
print(value2 * value1) #Multiplication
print(value2 / value1) #Division

Name = "Tyree"
Num = 2

# all functions below give the user a boolean value back. 

print(Name.isalpha()) #checks if the value is alphabetical 
print(str(Num).isalpha()) # "isalpha can only take a string value 
print(Name.isdigit()) # checks if the string value given is a digits
print(Name.startswith("T")) # checks if the beginning of the string starts with teh given Char

```
