---
author: Ionut
pubDatetime: 2024-10-14T19:44:00Z 
title: Operatori Tip0093 Sizeof.c
slug: Sizeof.c
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
   printf("Variables of type int use %d bytes\n", sizeof(int));
   printf("Variables of type float use %d bytes\n", sizeof(float));
   printf("Variables of type double use %d bytes\n", sizeof(double));
   printf("Variables of type unsigned use %d bytes\n", sizeof(unsigned));
   printf("Variables of type long use %d bytes\n", sizeof(long));
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++printf%28%22Variables+of+type+int+use+%25d+bytes%5Cn%22%2C+sizeof%28int%29%29%3B%0D%0A+++printf%28%22Variables+of+type+float+use+%25d+bytes%5Cn%22%2C+sizeof%28float%29%29%3B%0D%0A+++printf%28%22Variables+of+type+double+use+%25d+bytes%5Cn%22%2C+sizeof%28double%29%29%3B%0D%0A+++printf%28%22Variables+of+type+unsigned+use+%25d+bytes%5Cn%22%2C+sizeof%28unsigned%29%29%3B%0D%0A+++printf%28%22Variables+of+type+long+use+%25d+bytes%5Cn%22%2C+sizeof%28long%29%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>