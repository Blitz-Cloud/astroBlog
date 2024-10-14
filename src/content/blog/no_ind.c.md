---
author: Ionut
pubDatetime: 2024-10-14T19:17:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0108 no_ind.c
slug: no_ind.c
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
int age = 10;
int user_has_dog = 0;   // 0 is false
if (age == 10)
{
printf("Dogs are important pets\n");
if (! user_has_dog)
printf("You should get a dalmatian\n");
}
printf("Happy is a dalmatian\n");
}

```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A%7B+%0D%0Aint+age+%3D+10%3B%0D%0Aint+user_has_dog+%3D+0%3B+++%2F%2F+0+is+false%0D%0Aif+%28age+%3D%3D+10%29%0D%0A%7B%0D%0Aprintf%28%22Dogs+are+important+pets%5Cn%22%29%3B%0D%0Aif+%28%21+user_has_dog%29%0D%0Aprintf%28%22You+should+get+a+dalmatian%5Cn%22%29%3B%0D%0A%7D%0D%0Aprintf%28%22Happy+is+a+dalmatian%5Cn%22%29%3B%0D%0A%7D%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>