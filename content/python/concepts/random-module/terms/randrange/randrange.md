---
Title: "random.randrange()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Random"
  - "Functions"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
  - "https://www.codecademy.com/learn/paths/data-science"
---

## Definition

Generates random numbers from a defined range of `int` values.

## Syntax

```py
random.randrange(start, stop, steps)
```

## Example 1

Use `random.randrange()` to return a random number between `0` and `99`:

```codebyte/python
import random

print(random.randrange(0, 100))
```

## Example 2

Use `random.randrange()` to return a random number between `0` and `99` and is divisible by `5`:

```codebyte/python
import random

print(random.randrange(0, 100, 5))
```
