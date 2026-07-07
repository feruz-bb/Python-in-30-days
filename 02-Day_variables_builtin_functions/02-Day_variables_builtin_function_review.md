# Day 2 Review

## Review Schedule

| Field | Value |
|---|---|
| First review | 2026-07-02 |
| Last review | 2026-07-04 |
| Next review | 2026-07-07 |
| Last score | Not scored yet (/60) |
| Weak topics | Fill after scoring |
| Status | Learning |

Default review intervals: same day, next day, 3 days, 7 days, 14 days, 30 days.

## Scoring Guide

| Score | Meaning |
|---|---|
| 0 | Forgot |
| 1 | Partial |
| 2 | Correct with effort |
| 3 | Easy |

## Summary

Day 2 focused on storing data with variables, choosing clear variable names, collecting user input, converting between types, and using built-in functions. The goal is to explain the rule, then prove it by writing or predicting small Python examples.

## Core Concepts

| Concept | Why it matters | Example |
|---|---|---|
| Variable names | Clear names make programs readable and valid. | `first_name = "Ada"` |
| snake_case | Python convention for readable variable names. | `is_married = False` |
| `input()` | Collects text from the user while the program runs. | `name = input("Name: ")` |
| Type conversion | Turns values into the type needed for an operation. | `age = int(input("Age: "))` |
| Built-in functions | Solve common tasks without writing them from scratch. | `len("Python")`, `type(10)` |

## Confidence Checklist

| Skill                                                          | Confidence 0/1/2/3 | Evidence |
| -------------------------------------------------------------- | -----------------: | -------- |
| I can explain Python variable naming rules.                    |                  3 |          |
| I can use snake_case correctly.                                |                  3 |          |
| I can declare multiple variables in one line.                  |                  3 |          |
| I can use `input()` to collect user data.                      |                  3 |          |
| I can identify common Python data types.                       |                  3 |          |
| I can convert values between types with built-in functions.    |                  3 |          |
| I can use `help('keywords')` to inspect Python reserved words. |                  3 |          |
| I can solve basic arithmetic exercises with variables.         |                  3 |          |
| I can calculate the area and circumference of a circle.        |                  3 |          |

## Question To Evaluate Learning

If you need to store a user's first name, age, and whether they are married, what variable names and data types would you choose, and why?

<details><summary>Answer</summary>

Use clear snake_case names and suitable data types, for example: `first_name` as a `str`, `age` as an `int`, and `is_married` as a `bool`. These names describe the data and the types match how each value should be used.

</details>

Score: 0/1/2/3  
Last reviewed: YYYY-MM-DD  
Next review: YYYY-MM-DD  
Mistake note:

## Brain Test Questions

### Recall Questions

Use these questions without looking at the notebook first.

1. What are the rules for naming a valid Python variable?
   <details><summary>Answer</summary>

   It must start with a letter or underscore, contain only letters, digits, and underscores, and not be a Python keyword.

   </details>

   Score: 0/1/2/**3**
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

2. Why is `first-name` an invalid variable name?
   <details><summary>Answer</summary>

   The hyphen is treated as a subtraction operator, not part of a variable name.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

3. What is snake_case, and why is it commonly used in Python?
   <details><summary>Answer</summary>

   Snake_case uses lowercase words separated by underscores, and it is the standard readable naming style in Python.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

4. What is the difference between `int`, `float`, and `str`?
   <details><summary>Answer</summary>

   `int` stores whole numbers, `float` stores decimal numbers, and `str` stores text.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

5. When would you use `input()` in a program?
   <details><summary>Answer</summary>

   Use it when you want to ask the user for data at runtime.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

6. What does `help('keywords')` show you?
   <details><summary>Answer</summary>

   It shows the list of Python reserved keywords.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

7. What does `len()` tell you about a string?
   <details><summary>Answer</summary>

   It returns the number of characters in the string.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

8. Can you declare multiple variables in one line? If yes, how?
   <details><summary>Answer</summary>

   Yes. For example: `a, b, c = 1, 2, 3`.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

### Explain Questions

1. What happens if you try to do arithmetic with a number stored as a string?
   <details><summary>Answer</summary>

   Python will treat it as text unless you convert it. Numeric arithmetic usually requires conversion with `int()` or `float()`.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

2. What is the difference between `list`, `tuple`, and `dict`?
   <details><summary>Answer</summary>

   A `list` is ordered and mutable, a `tuple` is ordered and immutable, and a `dict` stores key-value pairs.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

3. Why might `True` and `False` be useful when storing user information?
   <details><summary>Answer</summary>

   They let you store yes/no or on/off states clearly.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

4. How would you calculate the area of a circle if you know the radius?
   <details><summary>Answer</summary>

   Use `pi * radius ** 2`.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

5. Why is it important to use clear variable names?
   <details><summary>Answer</summary>

   Clear names make code easier to read, understand, and maintain.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

6. What is the difference between `//` and `/` in Python?
   <details><summary>Answer</summary>

   `/` performs true division and returns a float, while `//` performs floor division.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

7. What built-in functions did you use in Day 2, and what does each one do?
   <details><summary>Answer</summary>

   Common examples include `input()` for user input, `type()` for checking types, `int()`, `float()`, `str()`, and `list()` for converting values, `len()` for counting items, and `help()` for viewing documentation.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

## Apply With Code

1. Predict the output.

   ```python
   age = "20"
   print(age + "1")
   ```

   <details><summary>Answer</summary>

   ```python
   201
   ```

   Both values are strings, so `+` joins them instead of doing numeric addition.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

2. Write code that asks for a radius and prints the area of a circle.

   <details><summary>Answer</summary>

   ```python
   radius = float(input("Radius: "))
   pi = 3.14
   area = pi * radius ** 2
   print(area)
   ```

   `input()` returns text, so `float()` converts the radius before calculation.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

3. Fix the invalid variable name and keep the same meaning.

   ```python
   first-name = "Ada"
   ```

   <details><summary>Answer</summary>

   ```python
   first_name = "Ada"
   ```

   Python variable names cannot contain hyphens. Snake_case uses underscores.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

4. Predict the output.

   ```python
   first_name, age, is_married = "Ada", 28, False
   print(type(first_name))
   print(type(age))
   print(type(is_married))
   ```

   <details><summary>Answer</summary>

   ```python
   <class 'str'>
   <class 'int'>
   <class 'bool'>
   ```

   The assigned values are text, a whole number, and a boolean.

   </details>

   Score: 0/1/2/**3**  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

## Error Log

| Date | Question | Mistake | Correct idea |
|---|---|---|---|
| YYYY-MM-DD |  |  |  |

## Interleaving From Older Days

- Day 1: What does `print()` do?
- Day 1: Predict `5 // 2`, `5 / 2`, and `5 % 2`.
- Day 1: What type is `3.14`?
- Day 1: What is the difference between a `list` and a `set`?
- Day 1: Which operator performs exponentiation?
