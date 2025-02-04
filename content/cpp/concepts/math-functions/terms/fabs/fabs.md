---
Title: "fabs()"
Subjects:
  - "Computer Science"
Tags:
  - "Functions"
  - "Arithmetic"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-c-plus-plus"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

## Definition

Returns the absolute value of the floating point argument.

## Syntax

```cpp
std:fabs(n)
```

## Example 1

Use `fabs()` to return the absolute value of `-6.5`:

```cpp
#include <iostream>
#include <cmath> 

int main () {
  std::cout << std::fabs(-6.5) << "\n";
}

// Output: 6.5
```
