---
author: Ionut
pubDatetime: 2024-10-14T19:21:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0117 For_diff.c
slug: For_diff.c
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
   int counter;

   for (counter = -100; counter <= 100; counter += 5)
    printf("%d ", counter);

   printf("\nStarting second loop\n");
   
   for (counter = 100; counter >= -100; counter -= 25)
    printf("%d ", counter);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+counter%3B%0D%0A%0D%0A+++for+%28counter+%3D+-100%3B+counter+%3C%3D+100%3B+counter+%2B%3D+5%29%0D%0A++++printf%28%22%25d+%22%2C+counter%29%3B%0D%0A%0D%0A+++printf%28%22%5CnStarting+second+loop%5Cn%22%29%3B%0D%0A+++%0D%0A+++for+%28counter+%3D+100%3B+counter+%3E%3D+-100%3B+counter+-%3D+25%29%0D%0A++++printf%28%22%25d+%22%2C+counter%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>