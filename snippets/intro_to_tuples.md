---
title: intro to tuples
tags: collection,beginner
firstSeen: 2022-01-25T10:19:59+02:00
lastUpdated: 2022-01-25T19:27:07+02:00
---

Tuples are used to store multiple items in a single variable

- Tuples are a type of collection that is both ordered AND unchangeable
- You establish that it is a tuple by using round brackets


```py
def create_tuple(x,y,z):
    new_tuple = (x , y, z)
    return new_tuple
```

```py
x = "cows"
y= "gorillas"
z= "monkeys"
create_tuple(x,y,z) #'cows,gorillas,monkeys'
```
