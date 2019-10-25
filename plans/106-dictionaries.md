# Dictionaries

| | |
| --- | ---
| Concepts | Python, Dictionaries, Data Structures
| Objectives | Understand what a data structure is and be able to use a dictionary
| Take Home | Game State problems

## Introduction

### Classroom Rules
- Ask questions
- Interrupt me
- Computers are for code, not for notes

### Review
- Variables
- Truth
- If, elif, else
- Functions

## Lesson

1. Data Structures
    1. Data Structures are ways of storing data
    2. Data are just units of information
    3. Think of Data Structures like different types of writing
    4. Lists & Dictionaries
        1. Shopping list -> Indexes
        2. Encyclopedia -> Indexes
2. Dictionaries
    1. Dictionaries are a form of data structure that use key-based indexes (encyclopedia)
    2. _Demonstrate_ dictionary
    ```python
    book = {
        "title": "The Two Towers",
        "series": "Lord of the Rings"        
    }
    ```
    3. Dictionaries let us store a lot of data in one place
3. Example
    1. Coffee type -> Cofee maker
    ```python
    def make_coffee(blend, flavor, caffeine):
        # do stuff
    ```
    ```python
    coffee = {
        "blend": "dark",
        "flavor": "arabica",
        "caffeine": True,
    }
    ```
   ```python
   def make_coffee(coffee):
        if coffee["blend"] == "dark":
            print("Whoa! That's dark!")
        else:
            print("Weak.")
   ```
4. Nesting data
    ```
    game = {
        "player": {
            "health": 10
            "weapon": "sword"
        }
    }
    ```
5. Safety
    1. Now we can't always guarantee our data is there
    2. Python has the `in` keyword
6. Explain homework

