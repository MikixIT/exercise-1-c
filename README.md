# exercise-1-c
exercise-1-c | C | ask the user to enter the numbers that will , when 0 is entered I print the result

```c
//
//  main.c
//  exercise-1-c
//  ask the user to enter the numbers that will , when 0 is entered I print the result

//  Created by Michael Torres on 02/10/23.
//


#include <stdio.h>

int main(void) {
    int x , numbers = 0 ;
    
    while (x!=0) {
        printf("enter a number: ");
        scanf("%d", &x);
        numbers+=x;
    }
    // if u type a letter, is a mess lol
    
    printf("\n the sum of your typed numbers is:: %d \n", numbers);
}
```
