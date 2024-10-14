---
author: Ionut
pubDatetime: 2024-10-14T19:57:00Z 
title: Printf Tip0062 Str_out.c
slug: Str_out.c
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
   char title[255] = "Jamsa\'s C/C++ Programmer\'s Bible";

   printf("The name of this book is %s\n", title);
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++char+title%5B255%5D+%3D+%22Jamsa%5C%27s+C%2FC%2B%2B+Programmer%5C%27s+Bible%22%3B%0D%0A%0D%0A+++printf%28%22The+name+of+this+book+is+%25s%5Cn%22%2C+title%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>