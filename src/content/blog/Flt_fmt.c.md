---
author: Ionut
pubDatetime: 2024-10-14T19:63:00Z 
title: Printf Tip0068 Flt_fmt.c
slug: Flt_fmt.c
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
   float value = 1.23456;

   printf ("%8.1f\n", value);
   printf ("%8.3f\n", value);
   printf ("%8.5f\n", value);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++float+value+%3D+1.23456%3B%0D%0A%0D%0A+++printf+%28%22%258.1f%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%258.3f%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%258.5f%5Cn%22%2C+value%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>