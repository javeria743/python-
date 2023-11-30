```python
#Creating Three variables
age = 21 # age variable
name = "Javeria"  # Name vaiable
is_student = True #boolean variable 
# Print variables
print("Name:", name)
print("Age:", age)
print("Is Student:", is_student)

```

    Name: Javeria
    Age: 21
    Is Student: True
    


```python
# Perform operations
age += 25  # Add 25 to age
full_name = name + " Smith."  # Concatenate name with "Smith."
is_student = not is_student  # Negate the boolean variable

# Print results
print("New Age:", age)
print("Full Name:", full_name)
print("Is Student:", is_student)
```

    New Age: 46
    Full Name: Javeria Smith.
    Is Student: False
    


```python
# Variables
width = 5.5
height = 3.25

# Calculating area
area = width * height

# Print the area
print("Area of the rectangle:", area)
```

    Area of the rectangle: 17.875
    


```python
# Temperature in Celsius
temperature_celsius = 25  #  temperature in celsius value

# Convert to Fahrenheit
temperature_fahrenheit = (temperature_celsius * 9/5) + 32

# Print the result
print("Temperature in Fahrenheit:", temperature_fahrenheit)
```

    Temperature in Fahrenheit: 77.0
    


```python
# Variable
radius = 5

# Calculate area of the circle
pi = 3.14159
area = pi * (radius ** 2)

# Print the result
print("Area of the circle:", area)
```

    Area of the circle: 78.53975
    


```python
# Creating a list of fruits
fruits = ["apple", "banana", "orange", "grape", "kiwi"]

# Print  list
print("List of fruits:", fruits)
```

    List of fruits: ['apple', 'banana', 'orange', 'grape', 'kiwi']
    


```python
# Creating a tuple of months
months = ("January", "February", "March")

# Print  tuple
print("Tuple of months:", months)
```

    Tuple of months: ('January', 'February', 'March')
    


```python
# List of numbers
numbers = [12, 34, 45, 67, 89, 100, 23, 56]

# Calculating sum and average
sum_of_numbers = sum(numbers)
average_of_numbers = sum_of_numbers / len(numbers)

# Print results
print("Sum of numbers:", sum_of_numbers)
print("Average of numbers:", average_of_numbers)
```

    Sum of numbers: 426
    Average of numbers: 53.25
    


```python
# Original list of fruits
fruits = ["apple", "banana", "orange", "grape", "kiwi"]

# Remove the first and last elements
fruits.pop(0)  # Removes the first element
fruits.pop(-1)  # Removes the last element

# Print updated list
print("Updated list of fruits:", fruits)
```

    Updated list of fruits: ['banana', 'orange', 'grape']
    


```python
# Creatin a dictionary named "capitals"
capitals = {"USA": "Washington D.C.","France": "Paris","Japan": "Tokyo"}
# Print dictionary
print(capitals)
```

    {'USA': 'Washington D.C.', 'France': 'Paris', 'Japan': 'Tokyo'}
    


```python
# Add a new country and its capital
capitals["Germany"] = "Berlin"

# Print updated dictionary
print(capitals)
```

    {'USA': 'Washington D.C.', 'France': 'Paris', 'Japan': 'Tokyo', 'Germany': 'Berlin'}
    


```python
# Checking if "France" exists in the dictionary
if "France" in capitals:
    print("France is in the dictionary.")
else:
    print("France is not in the dictionary.")
```

    France is in the dictionary.
    


```python
 # Taking user input and converting to integer in one line
number = int(input("Enter a number: "))

# Checking if the number is even or odd
if number % 2 == 0:
    print("The number is even.")
else:
    print("The number is odd.")
```

    Enter a number: 5
    The number is odd.
    


```python
# Assigning values to variables
age = 20  # age variable 
GPA = 3.5 #GPA variable 
# Checking eligibility for admission
if age >= 18 and GPA >= 3.0:
    print("Eligible for admission.")
else:
    print("Not eligible for admission.")
```

    Eligible for admission.
    


```python
# Creating a set named "fruits_set"
fruits_set = {"apple", "banana", "orange", "grape", "kiwi"}

# Print  set
print("Fruits Set:", fruits_set)
```

    Fruits Set: {'grape', 'orange', 'kiwi', 'banana', 'apple'}
    


```python
# Given sets
set1 = {1, 2, 3, 4, 5}
set2 = {3, 4, 5, 6, 7}

# Union of sets
union_set = set1.union(set2)
print("Union of sets:", union_set)
```

    Union of sets: {1, 2, 3, 4, 5, 6, 7}
    


```python
# Intersection of sets
intersection_set = set1.intersection(set2)
print("Intersection of sets:", intersection_set)
```

    Intersection of sets: {3, 4, 5}
    


```python
# Difference between sets (elements in set1 but not in set2)
difference_set1 = set1.difference(set2)
print("Difference (set1 - set2):", difference_set1)
```

    Difference (set1 - set2): {1, 2}
    


```python
# Difference between sets (elements in set1 but not in set2)
difference_set1 = set1.difference(set2)
print("Difference (set1 - set2):", difference_set1)
```

    Difference (set1 - set2): {1, 2}
    


```python
# Creating a string variable
sentence = "Python programming is fun and powerful!"

# Findinf the length of the string
length_of_string = len(sentence)
print("Length of the string:", length_of_string)
```

    Length of the string: 39
    


```python
# Converting the string to uppercase
uppercase_sentence = sentence.upper()
print("Uppercase string:", uppercase_sentence)
```

    Uppercase string: PYTHON PROGRAMMING IS FUN AND POWERFUL!
    


```python
# Replacing "fun" with "exciting"
modified_sentence = sentence.replace("fun", "exciting")
print("Modified string:", modified_sentence)
```

    Modified string: Python programming is exciting and powerful!
    


```python
# Checking if the string contains the word "Python"
contains_python = "Python" in sentence
print("Does the string contain the word 'Python'?", contains_python)
```

    Does the string contain the word 'Python'? True
    


```python
# Spliting the string into a list of words
word_list = sentence.split()
print("List of words:", word_list)
```

    List of words: ['Python', 'programming', 'is', 'fun', 'and', 'powerful!']
    


```python

```
