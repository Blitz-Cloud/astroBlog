---
author: Ionut
pubDatetime: 2024-10-14T19:51:00Z 
title: Printf Tip0056 U_intout.c
slug: U_intout.c
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
   unsigned int value = 42000;

   printf("Displaying 42000 as unsigned %u\n", value);
   printf("Displaying 42000 as int %d\n", value);
 }



```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++unsigned+int+value+%3D+42000%3B%0D%0A%0D%0A+++printf%28%22Displaying+42000+as+unsigned+%25u%5Cn%22%2C+value%29%3B%0D%0A+++printf%28%22Displaying+42000+as+int+%25d%5Cn%22%2C+value%29%3B%0D%0A+%7D%0D%0A%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>