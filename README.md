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
```python
Developed By : SANJAY M
Register No  : 212223230187
```

```python
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
 {
    srand(time(0));  
    int random = rand(); 
    printf("Random number: %d\n", random); 
    return 0;
}
```
# OUTPUT:
![Screenshot 2025-04-15 141137](https://github.com/user-attachments/assets/d72dadf8-94ba-46d5-975e-7830e0161266)


# RESULT:
Thus the program for pseudorandom number generation successfully executed.
