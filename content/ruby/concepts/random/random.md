---
Title: "Random"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Functions"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-ruby"
  - "https://www.codecademy.com/learn/learn-rails"
---

The `rand` function will return a random number greater than or equal to 0 and less than the integer passed to the function. If an argument is not passed to the function, the return value is a random number between 0 and 1.

## Example

```ruby
# When no argument is passed, the result is a random number between 0 and 1.
puts rand();
# Output example: 0.5
```

```ruby

# When an argument is passed, the result is a random number between 0 and the argument.
puts rand(10);
# Output example: 6
```
