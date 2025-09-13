NAME : VISWAJITH LALITHRAM R.V

REG.NO : 212224240187

---

# EX-NO-6-Pseudo-Random-Number

---

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

---

# ALGORITHM:
--> Start the program and import the required libraries.

--> Seed the random number generator using the current time(i.e) rand(time(0));

--> Get the number of randon number to generate.

--> Pass the value for number of iterations and print the numbers.

--> End the program.

---

# PROGRAM:

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int count, min, max;
    
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);

    printf("Enter the minimum value: ");
    scanf("%d", &min);

    printf("Enter the maximum value: ");
    scanf("%d", &max);

    srand(time(NULL));
    printf("Pseudorandom numbers:\n");

    for (int i = 0; i < count; i++)
        printf("%d\n", (rand() % (max - min + 1)) + min);

    return 0;
}

```

---

# OUTPUT:


<img width="1347" height="673" alt="Screenshot 2025-09-13 082033" src="https://github.com/user-attachments/assets/9be452cb-0858-45ce-b103-d6c254434767" />


---

# RESULT:

Implementation of Pseudorandom Number Generation Using Standard library was Successful.....
