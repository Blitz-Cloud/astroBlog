---
author: Ionut
pubDatetime: 2024-10-14T19:27:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0125 Do_menu.c
slug: Do_menu.c
featured: false
draft: false
tags:
  - c
  - poli
description: exemple de cod
---
```c
#include <stdio.h>
#include <conio.h>
#include <ctype.h>
#include <stdlib.h>

int main(int)
 {
   char letter;
   
   do
	{
     printf("A Display directory listing\n");
     printf("B Change system time\n");
     printf("C Change system date\n");
     printf("Q Quit\n");
     printf("Choice: ");
     
     letter = getch();     
     letter = toupper(letter);

     if (letter == 'A')
       system("DIR");
     else if (letter == 'B')
       system("TIME");
     else if (letter == 'C')
       system("DATE");
    }
   while (letter != 'Q');
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%23include+%3Cconio.h%3E%0D%0A%23include+%3Cctype.h%3E%0D%0A%23include+%3Cstdlib.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++char+letter%3B%0D%0A+++%0D%0A+++do%0D%0A%09%7B%0D%0A+++++printf%28%22A+Display+directory+listing%5Cn%22%29%3B%0D%0A+++++printf%28%22B+Change+system+time%5Cn%22%29%3B%0D%0A+++++printf%28%22C+Change+system+date%5Cn%22%29%3B%0D%0A+++++printf%28%22Q+Quit%5Cn%22%29%3B%0D%0A+++++printf%28%22Choice%3A+%22%29%3B%0D%0A+++++%0D%0A+++++letter+%3D+getch%28%29%3B+++++%0D%0A+++++letter+%3D+toupper%28letter%29%3B%0D%0A%0D%0A+++++if+%28letter+%3D%3D+%27A%27%29%0D%0A+++++++system%28%22DIR%22%29%3B%0D%0A+++++else+if+%28letter+%3D%3D+%27B%27%29%0D%0A+++++++system%28%22TIME%22%29%3B%0D%0A+++++else+if+%28letter+%3D%3D+%27C%27%29%0D%0A+++++++system%28%22DATE%22%29%3B%0D%0A++++%7D%0D%0A+++while+%28letter+%21%3D+%27Q%27%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>