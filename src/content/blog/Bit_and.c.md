---
author: Ionut
pubDatetime: 2024-10-14T19:41:00Z 
title: Operatori Tip0088 Bit_and.c
slug: Bit_and.c
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
   printf("0 & 0 is %d\n", 0 & 0);
   printf("0 & 1 is %d\n", 0 & 1);
   printf("1 & 1 is %d\n", 1 & 1);
   printf("1 & 2 is %d\n", 1 & 2);
   printf("15 & 127 is %d\n", 15 & 127);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++printf%28%220+%26+0+is+%25d%5Cn%22%2C+0+%26+0%29%3B%0D%0A+++printf%28%220+%26+1+is+%25d%5Cn%22%2C+0+%26+1%29%3B%0D%0A+++printf%28%221+%26+1+is+%25d%5Cn%22%2C+1+%26+1%29%3B%0D%0A+++printf%28%221+%26+2+is+%25d%5Cn%22%2C+1+%26+2%29%3B%0D%0A+++printf%28%2215+%26+127+is+%25d%5Cn%22%2C+15+%26+127%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>