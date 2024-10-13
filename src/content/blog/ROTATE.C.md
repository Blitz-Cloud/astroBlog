---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z 
title: Operatori Tip0095 ROTATE.C
slug: ROTATE.C
featured: false
draft: false
tags:
  - c
  - poli
description: exemple de cod
---
```c
#include <stdio.h>
#include <stdlib.h>

int main(int)
 {
   unsigned value = 1;

   printf("%u rotated right once is %u\n", value, _rotr(value, 1));
   value = 5;
   printf("%u rotated right twice is %u\n", value, _rotr(value, 2));
   value = 65534;
   printf("%u rotated left twice is %u\n", value, _rotl(value, 2));
 }



```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%23include+%3Cstdlib.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++unsigned+value+%3D+1%3B%0D%0A%0D%0A+++printf%28%22%25u+rotated+right+once+is+%25u%5Cn%22%2C+value%2C+_rotr%28value%2C+1%29%29%3B%0D%0A+++value+%3D+5%3B%0D%0A+++printf%28%22%25u+rotated+right+twice+is+%25u%5Cn%22%2C+value%2C+_rotr%28value%2C+2%29%29%3B%0D%0A+++value+%3D+65534%3B%0D%0A+++printf%28%22%25u+rotated+left+twice+is+%25u%5Cn%22%2C+value%2C+_rotl%28value%2C+2%29%29%3B%0D%0A+%7D%0D%0A%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>