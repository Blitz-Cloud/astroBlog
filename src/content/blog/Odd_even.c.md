---
author: Ionut
pubDatetime: 2024-10-14T19:29:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0126 Odd_even.c
slug: Odd_even.c
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

   printf("\nEven values\n");
   for (counter = 1; counter <= 100; counter++)
     {
       if (counter % 2)  // Odd
         continue;

       printf("%d ", counter);
     }

   printf("\nOdd values\n");
   counter = 0;
   while (counter <= 100) 
     {
       counter++;

       if (! (counter % 2)) // Even 
         continue;

       printf("%d ", counter);
     }
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+counter%3B%0D%0A%0D%0A+++printf%28%22%5CnEven+values%5Cn%22%29%3B%0D%0A+++for+%28counter+%3D+1%3B+counter+%3C%3D+100%3B+counter%2B%2B%29%0D%0A+++++%7B%0D%0A+++++++if+%28counter+%25+2%29++%2F%2F+Odd%0D%0A+++++++++continue%3B%0D%0A%0D%0A+++++++printf%28%22%25d+%22%2C+counter%29%3B%0D%0A+++++%7D%0D%0A%0D%0A+++printf%28%22%5CnOdd+values%5Cn%22%29%3B%0D%0A+++counter+%3D+0%3B%0D%0A+++while+%28counter+%3C%3D+100%29+%0D%0A+++++%7B%0D%0A+++++++counter%2B%2B%3B%0D%0A%0D%0A+++++++if+%28%21+%28counter+%25+2%29%29+%2F%2F+Even+%0D%0A+++++++++continue%3B%0D%0A%0D%0A+++++++printf%28%22%25d+%22%2C+counter%29%3B%0D%0A+++++%7D%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>