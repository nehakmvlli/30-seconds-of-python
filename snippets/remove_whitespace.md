---
title: remove whitespace
tags: string,beginner
firstSeen: 2022-01-25T10:19:59+02:00
lastUpdated: 2022-01-25T19:27:07+02:00
---

Removes all whitespace in a string.

- Utilizes the replace() function
- We replace all whitespace with "" (which is essentially is no space)

```py
def remove(string):
    return string.replace(" ", "")
```

```py
string = ' w h i t e s p a c e '
remove(string)  #'whitespace'
```
