# Python Data Structures Lab
In this lab, you’ll practice working with different data structures in Python, including lists, tuples, dictionaries, and more. By manipulating these data structures, you’ll gain a better understanding of how to organize and store data effectively in your Python programs.

By the end of this lab, you will be able to:

- Create and modify lists and tuples.
- Utilize dictionaries for more complex data storage.
- Iterate over data structures using loops.
- Apply Python’s slicing and indexing features to access data.

## Setup 
Open your Terminal application and navigate to your `~/code/ga/labs` directory:

```bash
cd ~/code/ga/labs
```

Make a new repository on GitHub named `python-data-structures-lab`.

Clone a copy of your remote repo locally by using the `git clone` command:

```bash
git clone https://github.com/<your-username>/python-data-structures-lab.git
```
> 📚 Note: In the link above, where it says `<your-username>`, you should see the username from your GitHub account.

Next, `cd` into your new cloned directory, `python-data-structures-lab`:

```bash
cd python-data-structures-lab
```

Create a file for the lesson:

```bash
touch exercises.py
```

Open the project’s folder in your code editor:

```bash
code .
```

## Exercises

### Getting Started
- For each exercise, copy the provided code into a new Python script file named `exercises.py`.
- Each exercise includes a function where you will write your code. The function structure helps you focus on working with the specific data structure required.
- Follow the exercise instructions carefully to complete the code.
- After completing each exercise, run `python3 exercises.py` in your terminal to see the output and test your code.
> If you encounter difficulties with the syntax for data structures, review the provided lesson materials or collaborate with your classmates.

Let’s dive in!

### Exercise 0: Example
```py
# Exercise 0: Example
#
# This is a practice exercise to familiarize you with basic Python data structures.
#
# Create a list called `example_list` and append three elements to it. Print each element using a loop.
#
# Requirements:
# - The list should contain any three elements of your choice.
# - Use a loop to print each element.

def example_list_function():
  example_list = ['element1', 'element2', 'element3']
  for element in example_list:
      print(element)

# Call the function and print each element
example_list_function()
```

### Exercise 1: List and Indexing
```py
# Exercise 1: List and Indexing
#
# Create a list named students containing at least three student names (strings).
# Assign the second student’s name to a variable named first_student.
# Assign the last student’s name to a variable named last_student.

def manage_students():
    # your code here

# Call the function and print the result
print('Exercise 1:', manage_students())
```

### Exercise 2: Loop and String Concatenation
```py
# Exercise 2: Loop and String Concatenation
#
# Create a tuple named foods containing the same number of foods (strings) as there are names in the students list.
# Create a variable named meal and assign an empty string to it.
# Use a for loop to iterate over the strings in foods and append each string to meal.

def combine_foods():
    # your code here

# Call the function and print the result
print('Exercise 2:', combine_foods())
```

### Exercise 3: Slicing Tuples
```py
# Exercise 3: Slicing Tuples
#
# Using the slice operator, assign a new tuple containing only the last two food strings in the foods to a variable named last_two_foods.

def slice_foods():
    # your code here

# Call the function and print the result
print('Exercise 3:', slice_foods())
```

### Exercise 4: Dictionaries and String Formatting
```py
# Exercise 4: Dictionaries and String Formatting
#
# Create a dictionary named home_town containing the keys of city, state, and population.
# Using the home_town dictionary, assign to a variable named home_town_message a string with this format: “I was born in <city>, <state> - population of <population>”

def hometown_info():
    # your code here

# Call the function and print the result
print('Exercise 4:', hometown_info())
```

### Exercise 5: Iterating Over Dictionary Items
```py
# Exercise 5: Iterating Over Dictionary Items
#
# Define an empty list named home_town_items.
# Use a for loop to iterate over the key: value pairs in the home_town dictionary and append a string with the following format to home_town_items: "<key> = <value>"

def list_home_town_items():
    # your code here

# Call the function and print the result
print('Exercise 5:', list_home_town_items())
```

### Exercise 6: Celebrate Students (Level-Up)
```py
# Exercise 6: Celebrate Students
#
# Using the list of students and a list comprehension, assign to a variable named awesome_students a new list containing strings.
# For example: ["Tina is awesome!", "Fred is awesome!", "Wilma is awesome!"]

def create_awesome_students():
    # your code here

# Call the function and print the result
print('Exercise 6:', create_awesome_students())
```

### Exercise 7: Filter Foods (Level-Up)
```py
# Exercise 7: Filter Foods
#
# Assign to a variable named foods_with_an_a the result of list comprehension that filters the foods tuple to only include food strings that contain the letter 'a'.
# For example, if foods is a tuple of ('Taco', 'Burrito', 'Sandwich'), foods_with_an_a would be a list equal to ['Taco', 'Sandwich']

def filter_foods_with_a():
    # your code here

# Call the function and print the result
print('Exercise 7:', filter_foods_with_a())
```
