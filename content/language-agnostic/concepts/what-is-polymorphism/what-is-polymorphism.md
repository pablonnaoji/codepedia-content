---
Title: "What is Polymorphism?"
Subjects:
  - "Computer Science"
  - "Web Development"
Tags:
  - "Best Practices"
  - "Memory"
Catalog Content:
  - "https://www.codecademy.com/learn/paths/code-foundations"
  - "https://www.codecademy.com/learn/paths/computer-science"
  - "https://www.codecademy.com/learn/paths/web-development"
---

Polymorphism is one of the four principles of Object Oriented Programming which promote dynamic inheritance of child classes from their parent class in order to make use these features themselves in code. 

With Polymorphism, child classes are able to inherit methods from their parent class for use. This ability to inherit functionality from parent classes not only speeds up the development process but helps us reason and understand our code more intuitively as we can see the correlation between objects for easier understanding and manipulation of source code. 

```py
from math import pi

class Shape:
    def __init__(self, name):
        self.name = name

    def area(self):
        pass

    def fact(self):
        return "I am a two-dimensional shape."

    def __str__(self):
        return self.name

class Square(Shape):
    def __init__(self, length):
        super().__init__("Square")
        self.length = length

    def area(self):
        return self.length**2

    def fact(self):
        return "Squares have each angle equal to 90 degrees."


class Circle(Shape):
    def __init__(self, radius):
        super().__init__("Circle")
        self.radius = radius

    def area(self):
        return pi*self.radius**2


a = Square(4)
b = Circle(7)
print(b)
print(b.fact())
print(a.fact())
print(b.area())
```
