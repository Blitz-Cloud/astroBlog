---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z 
title: Printf Tip0054 Intout.c
slug: Intout.c
featured: false
draft: false
tags:
  - c
  - poli
description: exemple de cod
---
```c
#include <stdio.h>

int main(int)
 {
   int age = 41;
   int height = 73;
   int weight = 165;

   printf("The user\'s age: %d weight: %d height: %d\n", age, weight, height);
   printf("%d plus %d equals %d\n", 1, 2, 1 + 2);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+age+%3D+41%3B%0D%0A+++int+height+%3D+73%3B%0D%0A+++int+weight+%3D+165%3B%0D%0A%0D%0A+++printf%28%22The+user%5C%27s+age%3A+%25d+weight%3A+%25d+height%3A+%25d%5Cn%22%2C+age%2C+weight%2C+height%29%3B%0D%0A+++printf%28%22%25d+plus+%25d+equals+%25d%5Cn%22%2C+1%2C+2%2C+1+%2B+2%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>