---
author: Ionut
pubDatetime: 2024-10-14T19:23:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0120 Infinite.c
slug: Infinite.c
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
   int i;
   int result = 0;
   int value = 1;

   for (i = 0; i < 100; i++)
    {
      printf("%d ", i);
      result = value * --i;   
    }
 
   printf("Result %d\n", result);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+i%3B%0D%0A+++int+result+%3D+0%3B%0D%0A+++int+value+%3D+1%3B%0D%0A%0D%0A+++for+%28i+%3D+0%3B+i+%3C+100%3B+i%2B%2B%29%0D%0A++++%7B%0D%0A++++++printf%28%22%25d+%22%2C+i%29%3B%0D%0A++++++result+%3D+value+%2A+--i%3B+++%0D%0A++++%7D%0D%0A+%0D%0A+++printf%28%22Result+%25d%5Cn%22%2C+result%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>