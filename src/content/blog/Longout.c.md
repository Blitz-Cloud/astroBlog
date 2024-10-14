---
author: Ionut
pubDatetime: 2024-10-13T20:00:00Z
modDatetime: 2024-10-12T13:39:00.00Z
title: Printf Tip0057 Longout.c
slug: Longout.c
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
   long int one_million = 1000000;

   printf ("One million is %ld\n", one_million);
   printf ("One million is %d\n", one_million);

 }


```

<a href='https://www.geeksforgeeks.org/format-specifiers-in-c/' target='_blank'>Documentatie format specifiers</a>

<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++long+int+one_million+%3D+1000000%3B%0D%0A%0D%0A+++printf+%28%22One+million+is+%25ld%5Cn%22%2C+one_million%29%3B%0D%0A+++printf+%28%22One+million+is+%25d%5Cn%22%2C+one_million%29%3B%0D%0A+%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>
