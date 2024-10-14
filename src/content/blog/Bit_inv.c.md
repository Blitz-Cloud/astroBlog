---
author: Ionut
pubDatetime: 2024-10-14T19:43:00Z 
title: Operatori Tip0090 Bit_inv.c
slug: Bit_inv.c
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
   int value = 0xFF;

   printf("The inverse of %X is %X\n", value, ~value);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+value+%3D+0xFF%3B%0D%0A%0D%0A+++printf%28%22The+inverse+of+%25X+is+%25X%5Cn%22%2C+value%2C+~value%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>