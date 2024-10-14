---
author: Ionut
pubDatetime: 2024-10-14T19:20:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0116 For_down.c
slug: For_down.c
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

   for (counter = 5; counter >= 1; counter--)
    printf("%d ", counter);

   printf("\nStarting second loop\n");
   
   for (counter = 10; counter >= 1; counter--)
    printf("%d ", counter);

   printf("\nStarting third loop\n");

   for (counter = 0; counter >= 1; counter--)
    printf("%d ", counter);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+counter%3B%0D%0A%0D%0A+++for+%28counter+%3D+5%3B+counter+%3E%3D+1%3B+counter--%29%0D%0A++++printf%28%22%25d+%22%2C+counter%29%3B%0D%0A%0D%0A+++printf%28%22%5CnStarting+second+loop%5Cn%22%29%3B%0D%0A+++%0D%0A+++for+%28counter+%3D+10%3B+counter+%3E%3D+1%3B+counter--%29%0D%0A++++printf%28%22%25d+%22%2C+counter%29%3B%0D%0A%0D%0A+++printf%28%22%5CnStarting+third+loop%5Cn%22%29%3B%0D%0A%0D%0A+++for+%28counter+%3D+0%3B+counter+%3E%3D+1%3B+counter--%29%0D%0A++++printf%28%22%25d+%22%2C+counter%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>