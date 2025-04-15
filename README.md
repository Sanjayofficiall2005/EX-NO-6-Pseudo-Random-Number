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
Developed By  : SANJAY M
Register No   : 212223230187
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
![image](https://github.com/user-attachments/assets/619e71ac-f01f-4a89-88d3-ee21627668a9)

# RESULT:
Thus the program for pseudorandom number generation successfully executed.
