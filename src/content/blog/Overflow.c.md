---
author: Ionut
pubDatetime: 2024-10-14T19:47:00Z 
title: Precizia Variabilelor Tip0050 Overflow.c
slug: Overflow.c
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
   int positive = 32767;
   int negative = -32768;

   printf("%d + 1 is %d\n", positive, positive+1);
   printf("%d - 1 is %d\n", negative, negative-1);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+positive+%3D+32767%3B%0D%0A+++int+negative+%3D+-32768%3B%0D%0A%0D%0A+++printf%28%22%25d+%2B+1+is+%25d%5Cn%22%2C+positive%2C+positive%2B1%29%3B%0D%0A+++printf%28%22%25d+-+1+is+%25d%5Cn%22%2C+negative%2C+negative-1%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>