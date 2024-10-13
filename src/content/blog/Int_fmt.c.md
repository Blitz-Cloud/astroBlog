---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z 
title: Printf Tip0065 Int_fmt.c
slug: Int_fmt.c
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

   printf ("%1d\n", value);
   printf ("%2d\n", value);
   printf ("%3d\n", value);
   printf ("%4d\n", value);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+value+%3D+5%3B%0D%0A%0D%0A+++printf+%28%22%251d%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%252d%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%253d%5Cn%22%2C+value%29%3B%0D%0A+++printf+%28%22%254d%5Cn%22%2C+value%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>