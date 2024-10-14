---
author: Ionut
pubDatetime: 2024-10-14T19:22:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0118 For_more.c
slug: For_more.c
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
   char letter;
   float percent;

   for (letter = 'A'; letter <= 'Z'; letter++)
     putchar(letter);

   for (letter = 'z'; letter >= 'a'; letter--)
     putchar(letter);

   putchar('\n');

   for (percent = 0.0; percent < 1.0; percent += 0.1)
     printf("%3.1f\n", percent);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++char+letter%3B%0D%0A+++float+percent%3B%0D%0A%0D%0A+++for+%28letter+%3D+%27A%27%3B+letter+%3C%3D+%27Z%27%3B+letter%2B%2B%29%0D%0A+++++putchar%28letter%29%3B%0D%0A%0D%0A+++for+%28letter+%3D+%27z%27%3B+letter+%3E%3D+%27a%27%3B+letter--%29%0D%0A+++++putchar%28letter%29%3B%0D%0A%0D%0A+++putchar%28%27%5Cn%27%29%3B%0D%0A%0D%0A+++for+%28percent+%3D+0.0%3B+percent+%3C+1.0%3B+percent+%2B%3D+0.1%29%0D%0A+++++printf%28%22%253.1f%5Cn%22%2C+percent%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>