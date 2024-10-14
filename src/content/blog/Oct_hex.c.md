---
author: Ionut
pubDatetime: 2024-10-14T19:50:00Z 
title: Printf Tip0055 Oct_hex.c
slug: Oct_hex.c
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
   int value = 255;

   printf("The decimal value %d in octal is %o\n", value, value);
   printf("The decimal value %d in hexadecimal is %x\n", value, value);
   printf("The decimal value %d in hexadecimal is %X\n", value, value);
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+value+%3D+255%3B%0D%0A%0D%0A+++printf%28%22The+decimal+value+%25d+in+octal+is+%25o%5Cn%22%2C+value%2C+value%29%3B%0D%0A+++printf%28%22The+decimal+value+%25d+in+hexadecimal+is+%25x%5Cn%22%2C+value%2C+value%29%3B%0D%0A+++printf%28%22The+decimal+value+%25d+in+hexadecimal+is+%25X%5Cn%22%2C+value%2C+value%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>