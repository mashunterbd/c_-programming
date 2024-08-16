# c_-programming
My journey of learning C programming

first class:

basic C programming structure:

```c
#include <stdio.h>

int main() {
  printf("Hello World!");
  return 0;
}
```

![image](https://github.com/user-attachments/assets/866536de-9030-4565-adc2-8b107ffb2f5c)


# Single-line Comments
Example
```c
// This is a comment
printf("Hello World!");
```
```c
printf("Hello World!"); // This is a comment
```

# C Multi-line Comments
Multi-line comments start with /* and ends with */.

Any text between /* and */ will be ignored by the compiler:

Example
```c
/* The code below will print the words Hello World!
to the screen, and it is amazing */
printf("Hello World!");
```

# C Variables
![image](https://github.com/user-attachments/assets/171feea9-8471-447a-b2b3-43312a9d9716)
```c
int - 123 or -123
float - 19.99 or -19.99
char - 'a' or 'B'.
```
![image](https://github.com/user-attachments/assets/bca416b6-7ed9-4e25-865b-bbbb7918694d)
![image](https://github.com/user-attachments/assets/a26e9e44-fedd-4f93-9bbe-0f3435f982b0)

You can also declare a variable without assigning the value, and assign the value later:

Example

```c
// Declare a variable
int myNum;

// Assign a value to the variable
myNum = 15;
```

Certainly! Here's a refined explanation of format specifiers in C, along with examples:

---

### Format Specifiers

Format specifiers are used in conjunction with the printf() function to inform the compiler about the type of data a variable holds. They act as placeholders for the variable's value.

A format specifier begins with a percentage sign %, followed by a character that indicates the type of data.

**Example**: To output the value of an int variable, you would use the format specifier %d within double quotes ("") in the printf() function:

```c
int myNum = 15;
printf("%d", myNum);  // Outputs: 15
```


### Other Format Specifiers

- **%c**: Used for characters.
- **%f**: Used for floating-point numbers.
 
  **Example**:
   ```c
    // Create variables
    int myNum = 15;            // Integer (whole number)
    float myFloatNum = 5.99;   // Floating point number
    char myLetter = 'D';       // Character

    // Print variables
    printf("%d\n", myNum);        // Outputs: 15
    printf("%f\n", myFloatNum);   // Outputs: 5.990000
    printf("%c\n", myLetter);     // Outputs: D
    ```


    ### Combining Text and Variables

    To print both text and a variable, separate them with a comma inside the printf() function.

    **Example**:
    ```c
    int myNum = 15;
    printf("My favorite number is: %d\n", myNum);  // Outputs: My favorite number is: 15
    ```


    ### Summary

- Use %d for integers.
- Use %f for floats.
- Use %c for characters.
- Combine text and variables by separating them with commas in printf().

# Print Values Without Variables
You can also just print a value without storing it in a variable, as long as you use the correct format specifier:

Example
```C
printf("My favorite number is: %d", 15);
printf("My favorite letter is: %c", 'D');
```
         



