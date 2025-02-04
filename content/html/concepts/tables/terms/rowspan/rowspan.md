---
Title: "rowspan"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Tables"
  - "Elements"
  - "Web Development"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-html"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition 

Specifies the number of rows a cell should span. 

## Syntax

```html
<table>
  <tr>
    <th>Cell 1</th>
    <th>Cell 2</th>
  </tr>
  <tr>
    <td>Cell 3</td>
    <!-- Spans two rows -->
    <td rowspan="2">Cell 4</td>
  </tr>
  <tr>
    <td>Cell 5</td>
  </tr>
</table>
```

The following elements support colspan:

- `<td>`
- `<th>`
 
## Example 1

A table with a cell that spans two rows.

```html
<table>
  <tr>
    <th colspan="2">Languages and Frameworks</th>
  </tr>
  <tr>
    <td>Python</td>
    <td>Django</td>
  </tr>
  <tr>
    <td rowspan="2">JavaScript</td>
    <td>React.js</td>
  </tr>
  <tr>
    <td>Vue.js</td>
  </tr>
  <tr>
    <td>Ruby</td>
    <td>Ruby on Rails</td>
  </tr>
</table>
```

![Table with cell that spans two rows](https://raw.githubusercontent.com/Codecademy/docs/main/media-file-hosting/html-rowspan.png)
