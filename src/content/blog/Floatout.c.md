---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z 
title: Printf Tip0058 Floatout.c
slug: Floatout.c
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
   float price = 525.75;
   float sales_tax = 0.06; 

   printf("The item cost is %f\n", price);
   printf("Sales tax on the item is %f\n", price * sales_tax);
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++float+price+%3D+525.75%3B%0D%0A+++float+sales_tax+%3D+0.06%3B+%0D%0A%0D%0A+++printf%28%22The+item+cost+is+%25f%5Cn%22%2C+price%29%3B%0D%0A+++printf%28%22Sales+tax+on+the+item+is+%25f%5Cn%22%2C+price+%2A+sales_tax%29%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>