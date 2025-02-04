---
Title: ".split()"
Subjects:
  - "Web Development"
  - "Computer Science"
Tags:
  - "Strings"
  - "Methods"
Catalog Content:
  - "https://www.codecademy.com/learn/introduction-to-javascript"
  - "https://www.codecademy.com/learn/paths/web-development"
---

## Definition

Breaks the string on which it called into an array of substrings, and returns the new array. 

## Syntax

```js
string.split(separator);
```

The `separator` (optional) describes the pattern where each split should occur. It may be a string or a regular expression. If not provided, the returned array will contain the entire string as its lone element.

```js
string.split(separator, limit);
```

The `limit` (optional) determines the number of substring elements included in the array.  

## Examples

Split string into array of names:

```js
const stringOfPeople = 'Dominic, Shelly, Luka, Devin';

const arrayOfPeople = stringOfPeople.split(', ');

console.log(arrayOfPeople);
// Output: ['Dominic', 'Shelly, 'Luka, 'Devin']
```

Limit the number of names in array to three:

```js
const stringOfPeople = 'Dominic, Shelly, Luka, Devin';

const arrayOfPeople = stringOfPeople.split(', ', 3);

console.log(arrayOfPeople);
// Output: ['Dominic', 'Shelly, 'Luka']
```

Split string without providing a separator argument:

```js
const stringOfPeople = 'Dominic, Shelly, Luka, Devin';

const arrayOfPeople = stringOfPeople.split();

console.log(arrayOfPeople);
// Output: ['Dominic, Shelly, Luka, Devin']
```

Split string on each character:
```js
const letters = 'abcde';

const lettersArray = letters.split('');

console.log(lettersArray);
// Output: ['a', 'b', 'c', 'd', 'e']
```
