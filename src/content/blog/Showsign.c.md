---
author: Ionut
pubDatetime: 2024-10-14T19:59:00Z 
title: Printf Tip0064 Showsign.c
slug: Showsign.c
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
   int neg_int = -5;
   int pos_int = 5;  
   float neg_flt = -100.23;
   float pos_flt = 100.23;

   printf("The integer values are %+d and %+d\n", neg_int, pos_int);
   printf("The floating point values are %+f %+f\n", neg_flt, pos_flt);
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+neg_int+%3D+-5%3B%0D%0A+++int+pos_int+%3D+5%3B++%0D%0A+++float+neg_flt+%3D+-100.23%3B%0D%0A+++float+pos_flt+%3D+100.23%3B%0D%0A%0D%0A+++printf%28%22The+integer+values+are+%25%2Bd+and+%25%2Bd%5Cn%22%2C+neg_int%2C+pos_int%29%3B%0D%0A+++printf%28%22The+floating+point+values+are+%25%2Bf+%25%2Bf%5Cn%22%2C+neg_flt%2C+pos_flt%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>