---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z 
title: Printf Tip0060 Exp_out.c
slug: Exp_out.c
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
   float pi = 3.14159;
   float radius = 2.0031;

   printf("The circle's area is %e\n", 2 * pi * radius);
   printf("The circle's area is %E\n", 2 * pi * radius);
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++float+pi+%3D+3.14159%3B%0D%0A+++float+radius+%3D+2.0031%3B%0D%0A%0D%0A+++printf%28%22The+circle%27s+area+is+%25e%5Cn%22%2C+2+%2A+pi+%2A+radius%29%3B%0D%0A+++printf%28%22The+circle%27s+area+is+%25E%5Cn%22%2C+2+%2A+pi+%2A+radius%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>