---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z 
title: Operatori Tip0086 Postpre.c
slug: Postpre.c
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
   int value = 1;
   
   printf("Using postfix %d\n", value--); 
   printf("Value after decrement %d\n", value);
   value = 1;
   printf("Using prefix %d\n", --value); 
   printf("Value after decrement %d\n", value);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B+%0D%0A+++int+value+%3D+1%3B%0D%0A+++%0D%0A+++printf%28%22Using+postfix+%25d%5Cn%22%2C+value--%29%3B+%0D%0A+++printf%28%22Value+after+decrement+%25d%5Cn%22%2C+value%29%3B%0D%0A+++value+%3D+1%3B%0D%0A+++printf%28%22Using+prefix+%25d%5Cn%22%2C+--value%29%3B+%0D%0A+++printf%28%22Value+after+decrement+%25d%5Cn%22%2C+value%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>