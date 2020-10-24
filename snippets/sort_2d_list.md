---
title: sort_2d_list
tags: list,sort,intermediate
---

Sort 2 dimensional list.

- Use lambda function to generate key for itteration.

```py
def sort2D(lst):
    lst.sort(key = lambda x: x[1], reverse=True)
    return lst
```

```py
lst2d = [["Kylian Mbappé", 28, 14], ["Cristiano Ronaldo", 34, 5], ["Lionel Messi", 29, 20]]
sort2D(lst2d)
```
