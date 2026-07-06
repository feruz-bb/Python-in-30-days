# Day 3 Review

## Review Schedule

| Field | Value |
|---|---|
| First review | 2026-07-07 |
| Last review | 2026-07-07 |
| Next review | 2026-07-08 |
| Last score | Not scored yet (/60) |
| Weak topics | Fill after scoring |
| Status | New |

Default review intervals: same day, next day, 3 days, 7 days, 14 days, 30 days.

## Scoring Guide

| Score | Meaning |
|---|---|
| 0 | Forgot |
| 1 | Partial |
| 2 | Correct with effort |
| 3 | Easy |

## Summary

Day 3 focused on Python operators. You practiced arithmetic operators, assignment operators, comparison operators, identity and membership operators, and logical operators. The main goal is to predict what an expression returns, understand when the result is a number or a boolean, and use formulas in small Python scripts.

## Core Concepts

| Concept | Why it matters | Example |
|---|---|---|
| Boolean values | Many comparisons and logical checks return `True` or `False`. | `3 > 2` gives `True` |
| Arithmetic operators | They let you calculate values in code. | `2 ** 3`, `7 // 2`, `7 % 2` |
| Assignment operators | They update a variable using its current value. | `x += 3` means `x = x + 3` |
| Bitwise operators | They compare or shift the binary bits of integers. | `5 | 3`, `5 ^ 3`, `16 >> 3` |
| Comparison operators | They compare two values and return a boolean. | `len("mango") < len("avocado")` |
| Identity operators | They check whether two names point to the same object. | `x is y`, `x is not y` |
| Membership operators | They check whether something exists inside a sequence. | `"coding" in "coding for all"` |
| Logical operators | They combine or reverse boolean expressions. | `3 > 2 and 4 > 3` |
| Formula translation | Math formulas become code expressions. | `area = 3.14 * radius ** 2` |

## Confidence Checklist

| Skill | Confidence 0/1/2/3 | Evidence |
|---|---:|---|
| I can explain `True` and `False`. |  |  |
| I can use arithmetic operators correctly. |  |  |
| I can explain the difference between `/`, `//`, and `%`. |  |  |
| I can use `**` for exponentiation. |  |  |
| I can explain why `^` is not exponentiation in Python. |  |  |
| I can update variables with assignment operators like `+=` and `*=`. |  |  |
| I can compare values with `==`, `!=`, `>`, `<`, `>=`, and `<=`. |  |  |
| I can use `in` and `not in` with strings. |  |  |
| I can combine conditions with `and`, `or`, and `not`. |  |  |
| I can write small scripts for area, perimeter, slope, and distance. |  |  |

## Question To Evaluate Learning

If a program asks the user for the radius of a circle, which operators and type conversions do you need to calculate both area and circumference, and why?

<details><summary>Answer</summary>

Use `float(input(...))` because `input()` returns text and the radius may be decimal. Use multiplication `*` and exponentiation `**`.

```python
pi = 3.14
radius = float(input("Enter radius: "))
area = pi * radius ** 2
circumference = 2 * pi * radius
print(area)
print(circumference)
```

`radius ** 2` squares the radius. `2 * pi * radius` calculates the distance around the circle.

</details>

Score: 0/1/2/3  
Last reviewed: YYYY-MM-DD  
Next review: YYYY-MM-DD  
Mistake note:

## Brain Test Questions

Use these questions without looking at the notebook first.

### Recall Questions

1. What are the two boolean values in Python?
   <details><summary>Answer</summary>

   `True` and `False`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

2. Which operator performs exponentiation in Python?
   <details><summary>Answer</summary>

   `**` performs exponentiation. Example: `2 ** 3` gives `8`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

3. What is the difference between `/`, `//`, and `%`?
   <details><summary>Answer</summary>

   `/` gives true division, `//` gives floor division, and `%` gives the remainder.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

4. What does `x += 3` mean?
   <details><summary>Answer</summary>

   It means `x = x + 3`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

5. What does `x *= 3` mean?
   <details><summary>Answer</summary>

   It means `x = x * 3`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

6. What does `==` check?
   <details><summary>Answer</summary>

   It checks whether two values are equal.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

7. What does the `in` operator check?
   <details><summary>Answer</summary>

   It checks whether a value exists inside another value, such as a character or word inside a string.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

8. What do `and`, `or`, and `not` do?
   <details><summary>Answer</summary>

   `and` returns true only when both conditions are true. `or` returns true when at least one condition is true. `not` reverses a boolean result.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

### Explain Questions

1. Why does `7 / 2` return `3.5`, but `7 // 2` returns `3`?
   <details><summary>Answer</summary>

   `/` keeps the decimal part because it is true division. `//` performs floor division, so it returns the whole-number floor result.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

2. Why is `^` a common mistake for beginners coming from math notation?
   <details><summary>Answer</summary>

   In math, `^` is often used to mean exponentiation, but in Python it means bitwise XOR. Python uses `**` for exponentiation.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

3. Why does every comparison expression return either `True` or `False`?
   <details><summary>Answer</summary>

   A comparison asks a yes/no question about values. Python answers that question with a boolean value.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

4. What is the difference between `==` and `is`?
   <details><summary>Answer</summary>

   `==` checks value equality. `is` checks object identity, meaning whether two names refer to the same object.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

5. Why is `not 3 > 2` false?
   <details><summary>Answer</summary>

   `3 > 2` is `True`. `not True` becomes `False`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

6. How does `x >>= 3` relate to division by powers of 2?
   <details><summary>Answer</summary>

   Right shift moves the binary bits to the right. For positive integers, shifting right by `3` gives a result similar to floor-dividing by `2 ** 3`, which is `8`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

## Apply With Code

1. Predict the output.

   ```python
   print(7 / 2)
   print(7 // 2)
   print(7 % 2)
   ```

   <details><summary>Answer</summary>

   ```python
   3.5
   3
   1
   ```

   `7 / 2` keeps the decimal, `7 // 2` gives the floor result, and `7 % 2` gives the remainder.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

2. Predict the output.

   ```python
   a = 3
   b = 2
   print(a + b)
   print(a ** b)
   print(a % b)
   ```

   <details><summary>Answer</summary>

   ```python
   5
   9
   1
   ```

   `3 + 2` is `5`, `3 ** 2` is `9`, and `3 % 2` leaves remainder `1`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

3. Predict the output.

   ```python
   print(3 > 2 and 4 < 3)
   print(3 > 2 or 4 < 3)
   print(not 3 > 2)
   ```

   <details><summary>Answer</summary>

   ```python
   False
   True
   False
   ```

   The first expression needs both sides to be true. The second needs at least one side to be true. The last reverses `True` into `False`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

4. Write code that asks for the base and height of a triangle, then prints its area.

   <details><summary>Answer</summary>

   ```python
   base = float(input("Enter base: "))
   height = float(input("Enter height: "))
   area = 0.5 * base * height
   print(f"The area of the triangle is {area}")
   ```

   The formula is `0.5 * base * height`.

   </details>

   Score: 0/1/2/3  
   Last reviewed: YYYY-MM-DD  
   Next review: YYYY-MM-DD  
   Mistake note:

5. Write code to find the Euclidean distance between point `(2, 2)` and point `(6, 10)`.

   <details><summary>Answer</summary>

   ```python
   x1, y1 = 2, 2
   x2, y2 = 6, 10
   distance = ((x2 - x1) ** 2 + (y2 - y1) ** 2) ** 0.5
   print(distance)
   ```

   The distance is based on the square root of the sum of squared differences.

   </details>

   Score: 0/1/2/3  
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
- Day 2: What are the rules for valid Python variable names?
- Day 2: Why should you convert `input()` before doing numeric arithmetic?
- Day 2: What is the difference between `int`, `float`, `str`, and `bool`?
