---
Title: "re.sub()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Regular Expressions"
  - "Strings"
Catalog Content:
  - "https://www.codecademy.com/learn/introduction-to-regular-expressions"
  - "https://www.codecademy.com/learn/practical-data-cleaning"
  - "https://www.codecademy.com/learn/language-parsing"
  - "https://www.codecademy.com/learn/text-preprocessing"
---

## Definition

Replace matching substrings with a new string for all occurrences, or a specified number. 

## Syntax

```py
re.sub(<pattern>, <repl>, string, <count>, <flags>)
```

A `<pattern>` can include any of the following:

- A string: `Jane Smith` 
- A character class code: `/w`, `/s` , `/d`
- A regex symbol: `$`,  `|`,  `^`

The other arguments include:

- The replacement string (repl): `foo` 
- An integer value for the number of replacements (count): `10`
- Flags: `IGNORECASE`,  `VERBOSE`,  `DOTALL`

## Example 1

Replace all the occurrences of "BI" with "business intelligence":

```py
import re

blurb = '''The analytics firm uses a range of BI tools to  visualize data. Their internal data science team suggests 
    bi tools may be their most valuable resource.'''

re.sub(r'bi','business intelligence',blurb,flags=re.IGNORECASE)
# The ignorecase flag allows for matches regardless of case  
```

## Example 2

Replace all numerical values with "REDACTED":

```py
import re

confidential_str = '''The suspect's bank account (#333344444) and pin (#9999) were found in his cell'''

re.sub(r'\d+', 'REDACTED', confidential_str)
# \d mathes any numerical character 
```
