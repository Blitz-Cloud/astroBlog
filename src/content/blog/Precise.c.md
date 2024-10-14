---
author: Ionut
pubDatetime: 2024-10-14T19:48:00Z 
title: Precizia Variabilelor Tip0051 Precise.c
slug: Precise.c
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
   float accurate = 0.123456790987654321;
   double more_accurate = 0.1234567890987654321;

   printf("Value of float\t %21.19f\n", accurate);
   printf("Value of double\t %21.19f\n", more_accurate);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++float+accurate+%3D+0.123456790987654321%3B%0D%0A+++double+more_accurate+%3D+0.1234567890987654321%3B%0D%0A%0D%0A+++printf%28%22Value+of+float%5Ct+%2521.19f%5Cn%22%2C+accurate%29%3B%0D%0A+++printf%28%22Value+of+double%5Ct+%2521.19f%5Cn%22%2C+more_accurate%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>