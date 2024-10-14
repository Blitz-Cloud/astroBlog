---
author: Ionut
pubDatetime: 2024-10-14T19:61:00Z 
title: Printf Tip0066 Zero_pad.c
slug: Zero_pad.c
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
   int value = 5;

   printf ("%01d\n", value);
   printf ("%02d\n", value);
   printf ("%03d\n", value);
   printf ("%04d\n", value);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+value+%3D+5%3B%0D%0A%0D%0A+++printf+%28%22%2501d%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%2502d%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%2503d%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%2504d%5Cn%22%2C+value%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>