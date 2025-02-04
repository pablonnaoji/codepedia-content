---
Title: "Hooks"
Subjects:
  - "Web Development"
Tags:
  - "Functions"
  - "React"
Catalog Content:
  - "https://www.codecademy.com/learn/react-101"
  - "https://www.codecademy.com/learn/paths/web-development"
---

In React, hooks are functions that give function components class-like abilities. These abilities include:

- Using `state`
- Performing side effects

While there are standard React hooks, like `useState()` and `useEffect()`, there are also custom-made hooks!

Most hooks are imported from the `react` library:

```jsx
import React, { useState, useEffect } from "react";
```

## Syntax of useState()

Pass an `initialValue` into `useState()` to return a pair of new values:

- A current `state` value
- A function, `setState` that updates the `state`

```jsx
const [state, setState] = useState(initialValue);
```

## Syntax of useEffect()

Pass a callback function, `sideEffects()` into `useEffect()`. This hook and function will execute whenever the componnet mounts or updates. It is similar to React's lifecycle methods: `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`. The component's `state` can also be accessed inside of `sideEffect()`.

```jsx
useEffect(function sideEffects() {
  ...
})
```
