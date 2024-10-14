---
author: Ionut
pubDatetime: 2024-10-14T19:25:00Z 
title: 3 Instructiuni de decizie,selectie, ciclare(1) Instructiuni de decizie,selectie, ciclare Tip0123 Wait_yn.c
slug: Wait_yn.c
featured: false
draft: false
tags:
  - c
  - poli
description: exemple de cod
---
```c
#include <stdio.h>
#include <ctype.h>
#include <conio.h>

int main(int)
 {
   char letter;  												 // Letter typed by the user

   printf("Do you want to continue? (Y/N): ");

   letter = getch();         								 // Get the letter
   letter = toupper(letter);  							 // Convert letter to uppercase
   
   while ((letter != 'Y') && (letter != 'N'))
     {
       putch(7);      			      			      // Beep the speaker
       letter = getch();      			 			   // Get the letter
       letter = toupper(letter);						   // Convert letter to uppercase
     }

   printf("\nYour response was %c\n", letter);
 }


```
<a href='https://cpp.sh/?source=%23include+%3Cstdio.h%3E%0D%0A%23include+%3Cctype.h%3E%0D%0A%23include+%3Cconio.h%3E%0D%0A%0D%0Aint+main%28int%29%0D%0A+%7B%0D%0A+++char+letter%3B++%09%09%09%09%09%09%09%09%09%09%09%09+%2F%2F+Letter+typed+by+the+user%0D%0A%0D%0A+++printf%28%22Do+you+want+to+continue%3F+%28Y%2FN%29%3A+%22%29%3B%0D%0A%0D%0A+++letter+%3D+getch%28%29%3B+++++++++%09%09%09%09%09%09%09%09+%2F%2F+Get+the+letter%0D%0A+++letter+%3D+toupper%28letter%29%3B++%09%09%09%09%09%09%09+%2F%2F+Convert+letter+to+uppercase%0D%0A+++%0D%0A+++while+%28%28letter+%21%3D+%27Y%27%29+%26%26+%28letter+%21%3D+%27N%27%29%29%0D%0A+++++%7B%0D%0A+++++++putch%287%29%3B++++++%09%09%09++++++%09%09%09++++++%2F%2F+Beep+the+speaker%0D%0A+++++++letter+%3D+getch%28%29%3B++++++%09%09%09+%09%09%09+++%2F%2F+Get+the+letter%0D%0A+++++++letter+%3D+toupper%28letter%29%3B%09%09%09%09%09%09+++%2F%2F+Convert+letter+to+uppercase%0D%0A+++++%7D%0D%0A%0D%0A+++printf%28%22%5CnYour+response+was+%25c%5Cn%22%2C+letter%29%3B%0D%0A+%7D%0D%0A%0D%0A' target='_blank'> Ruleaza codul cu cpp.sh </a>