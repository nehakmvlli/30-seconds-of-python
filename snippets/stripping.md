---
title: stripping
tags: string,beginner
firstSeen: 2022-01-25T10:19:59+02:00
lastUpdated: 2022-01-25T19:27:07+02:00
---

Useful string function to help you remove any character from the ends of a string

- There are three types of functions that can be utilized : strip(), lstrip(), rstrip()
- strip() -> removes from both ends of the string
- lstrip() -> removes from the left end of the string
- rstrip() -> removes from the right end of the string
- Within the function you'd define which characters should be removed as the parameter

```py
def removeNonsense(string):
    return string.strip(",.yhelo")
```

```py
string = ",,,,,hello.....world...yyy"
removeNonsense(string)  #'world'
```
