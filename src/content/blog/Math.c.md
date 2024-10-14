---
author: Ionut
pubDatetime: 2024-10-14T19:35:00Z 
title: Operatori Tip0081 Math.c
slug: Math.c
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
   int seconds_in_an_hour;  
   float average;

   seconds_in_an_hour = 60 * 60;
   average = (5 + 10 + 15 + 20) / 4;
   printf("The number of seconds in an hour %d\n", seconds_in_an_hour);
   printf("The average of 5, 10, 15, and 20 is %f\n", average);
   printf("The number of seconds in 48 minutes is %d\n", seconds_in_an_hour - 12 * 60);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+seconds_in_an_hour%3B++%0D%0A+++float+average%3B%0D%0A%0D%0A+++seconds_in_an_hour+%3D+60+%2A+60%3B%0D%0A+++average+%3D+%285+%2B+10+%2B+15+%2B+20%29+%2F+4%3B%0D%0A+++printf%28%22The+number+of+seconds+in+an+hour+%25d%5Cn%22%2C+seconds_in_an_hour%29%3B%0D%0A+++printf%28%22The+average+of+5%2C+10%2C+15%2C+and+20+is+%25f%5Cn%22%2C+average%29%3B%0D%0A+++printf%28%22The+number+of+seconds+in+48+minutes+is+%25d%5Cn%22%2C+seconds_in_an_hour+-+12+%2A+60%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>