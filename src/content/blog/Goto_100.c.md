---
author: Ionut
pubDatetime: 2024-10-14T19:31:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0128 Goto_100.c
slug: Goto_100.c
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
   int count = 1;

   label:
     printf("%d ", count++);
     
     if (count <= 100)
       goto label;
 }

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++int+count+%3D+1%3B%0D%0A%0D%0A+++label%3A%0D%0A+++++printf%28%22%25d+%22%2C+count%2B%2B%29%3B%0D%0A+++++%0D%0A+++++if+%28count+%3C%3D+100%29%0D%0A+++++++goto+label%3B%0D%0A+%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>