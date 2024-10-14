---
author: Ionut
pubDatetime: 2024-10-14T19:33:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0130 Vowels.c
slug: Vowels.c
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

   int vowel_count = 0;
   
   for (letter = 'A'; letter <= 'Z'; letter++)
     switch (letter) {
       case 'A':
       case 'E':
       case 'I':
       case 'O':
       case 'U': vowel_count++;
     }; 
 
   printf("The number of vowels is %d\n", vowel_count);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++char+letter%3B%0D%0A%0D%0A+++int+vowel_count+%3D+0%3B%0D%0A+++%0D%0A+++for+%28letter+%3D+%27A%27%3B+letter+%3C%3D+%27Z%27%3B+letter%2B%2B%29%0D%0A+++++switch+%28letter%29+%7B%0D%0A+++++++case+%27A%27%3A%0D%0A+++++++case+%27E%27%3A%0D%0A+++++++case+%27I%27%3A%0D%0A+++++++case+%27O%27%3A%0D%0A+++++++case+%27U%27%3A+vowel_count%2B%2B%3B%0D%0A+++++%7D%3B+%0D%0A+%0D%0A+++printf%28%22The+number+of+vowels+is+%25d%5Cn%22%2C+vowel_count%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>