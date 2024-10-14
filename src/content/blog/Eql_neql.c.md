---
author: Ionut
pubDatetime: 2024-10-14T19:16:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0101 Eql_neql.c
slug: Eql_neql.c
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
   int age = 21;
   int height = 73;

   if (age == 21)
     printf("User\'s age is 21\n");

   if (age != 21)
     printf("User\'s age is not 21\n");

   if (height == 73)
     printf("User\'s height is 73\n");

   if (height != 73)
     printf("User\'s height is not 73\n");
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+age+%3D+21%3B%0D%0A+++int+height+%3D+73%3B%0D%0A%0D%0A+++if+%28age+%3D%3D+21%29%0D%0A+++++printf%28%22User%5C%27s+age+is+21%5Cn%22%29%3B%0D%0A%0D%0A+++if+%28age+%21%3D+21%29%0D%0A+++++printf%28%22User%5C%27s+age+is+not+21%5Cn%22%29%3B%0D%0A%0D%0A+++if+%28height+%3D%3D+73%29%0D%0A+++++printf%28%22User%5C%27s+height+is+73%5Cn%22%29%3B%0D%0A%0D%0A+++if+%28height+%21%3D+73%29%0D%0A+++++printf%28%22User%5C%27s+height+is+not+73%5Cn%22%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>