# CPP-Basics
Notes for C++ basics.

Author: Alexyy#4448 <br>
Edited By: None

# Variable definitions in C++

- cout: cout is an object of the class ostream. It is used to display output on the screen.
- cin: cin is an object of the class istream. It is used to take input from the keyboard.
- printf: printf is a function used to display output on the screen.
- endl: endl is a manipulator used to insert a new line in the output.

# Data types in C++
- int: int is a data type used to store integer values. (1, 2, 3, etc.)
- float: float is a data type used to store floating point values. (less precision than double)
- double: double is a data type used to store - floating point values. (more precision than float)
- char: char is a data type used to store character values. (a, b, c, etc.)
- bool: bool is a data type used to store boolean values. (true or false)
- void: void is a data type used to define functions that do not return any value.
<br>

# Example of a C++ program

Output: Hello World!
```cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello World!";
    return 0;
}

```

Output: Input a number and display it
```cpp
#include <iostream>
using namespace std;

int main()
{
    int num;
    cout << "Enter a number: ";
    cin >> num;
    cout << "You entered " << num;
    return 0;
}

```

Output: Input two numbers and display their sum
```cpp
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, sum;
    cout << "Enter two numbers: ";
    cin >> num1 >> num2;
    sum = num1 + num2;
    cout << "Sum = " << sum;
    return 0;
}

```

# Exit Codes

- 0: Successful execution
- 1: Unsuccessful execution
- 2: Invalid syntax
- 3: Invalid command
- 4: Invalid file name
- 5: Invalid directory name
- 6: Invalid path
- 7: Invalid drive
- 8: Invalid device
- 9: Invalid argument
- 10: Invalid parameter
<br>etc...
