---
Title: "thead"
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

Groups the header content in a table. 

## Syntax

```html
<thead>
  <!-- Takes in header content -->
</thead>
```

**Note:** The `<thead>` element is usually used along with `<tbody>` and `<tfoot>`. which provides useful semantic information. 

## Example

Grouping the header content in a table.

```html
<table>
  <!-- All header content will be inside the <thead> element -->
  <thead>
   <tr>
     <th>Company</th>
     <th>Phone</th>
   </tr>
  </thead>
  
  <!-- All body content will be inside the <tbody> element -->
  <tbody>
   <tr>
     <td>Apple</td>
     <td>iPhone</td>
   </tr>
   <tr>
     <td>Samsung</td>
     <td>Galaxy</td>
   </tr>
  </tbody>
</table>
```

| Company | Phone |
| --- | --- |
| Apple | iPhone |
| Samsung | Galaxy |
