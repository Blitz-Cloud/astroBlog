---
author: Ionut
pubDatetime: 2024-10-14T19:26:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0124 Item.c
slug: Item.c
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
   int counter = 1;  // Initialize the control variable

   while (counter <= 100)  // Test the control variable
     {
       printf("%d ", counter);  // Execute the statements

       counter++;    // Modify the control variable
     }
 }



```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29+%0D%0A+%7B%0D%0A+++int+counter+%3D+1%3B++%2F%2F+Initialize+the+control+variable%0D%0A%0D%0A+++while+%28counter+%3C%3D+100%29++%2F%2F+Test+the+control+variable%0D%0A+++++%7B%0D%0A+++++++printf%28%22%25d+%22%2C+counter%29%3B++%2F%2F+Execute+the+statements%0D%0A%0D%0A+++++++counter%2B%2B%3B++++%2F%2F+Modify+the+control+variable%0D%0A+++++%7D%0D%0A+%7D%0D%0A%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>