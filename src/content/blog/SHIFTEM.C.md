---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z 
title: Operatori Tip0094 SHIFTEM.C
slug: SHIFTEM.C
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
   unsigned u_val = 1;
   signed int value = -1;

   printf("%u (unsigned) shifted left 2 times is %u\n", u_val, u_val << 2);
   printf("%u (unsigned) shifted right 2 times is %u\n", u_val, u_val >> 2);
   u_val = 65535;
   printf("%u (unsigned) shifted left 2 times is %u\n", u_val, u_val << 2);
   printf("%u (unsigned) shifted right 2 times is %u\n", u_val, u_val >> 2);
   printf("%d (signed) shifted left 2 times is %d\n", value, value << 2);
   printf("%d (signed) shifted right 2 times is %d\n", value, value >> 2);
 }
```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++unsigned+u_val+%3D+1%3B%0D%0A+++signed+int+value+%3D+-1%3B%0D%0A%0D%0A+++printf%28%22%25u+%28unsigned%29+shifted+left+2+times+is+%25u%5Cn%22%2C+u_val%2C+u_val+%3C%3C+2%29%3B%0D%0A+++printf%28%22%25u+%28unsigned%29+shifted+right+2+times+is+%25u%5Cn%22%2C+u_val%2C+u_val+%3E%3E+2%29%3B%0D%0A+++u_val+%3D+65535%3B%0D%0A+++printf%28%22%25u+%28unsigned%29+shifted+left+2+times+is+%25u%5Cn%22%2C+u_val%2C+u_val+%3C%3C+2%29%3B%0D%0A+++printf%28%22%25u+%28unsigned%29+shifted+right+2+times+is+%25u%5Cn%22%2C+u_val%2C+u_val+%3E%3E+2%29%3B%0D%0A+++printf%28%22%25d+%28signed%29+shifted+left+2+times+is+%25d%5Cn%22%2C+value%2C+value+%3C%3C+2%29%3B%0D%0A+++printf%28%22%25d+%28signed%29+shifted+right+2+times+is+%25d%5Cn%22%2C+value%2C+value+%3E%3E+2%29%3B%0D%0A+%7D' target='_blank'> Ruleaza codul cu cpp.sh </a>