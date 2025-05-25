# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
~~~
 #include <stdio.h>
 #include <stdlib.h>
 #include <time.h>
 int main() {
 int i, n;
 srand(time(0));
 printf("Enter how many pseudorandom numbers you want to generate: ");
 scanf("%d", &n);
 printf("Generating %d pseudorandom numbers between 0 and 99:\n", n);
 for (i = 0; i < n; i++) {
 int randomNumber = rand() % 100;
 printf("%d ", randomNumber);
 }
 printf("\n");
 return 0;
 }
~~~
# OUTPUT:
![Screenshot 2025-05-26 000653](https://github.com/user-attachments/assets/aa6de2d0-4ad3-4b61-b5c3-52a4de9ed438)

# RESULT:
 The program is executed successfully.
