# Variable definitions in C++

- cout: cout is an object of the class ostream. It is used to display output on the screen.
- cin: cin is an object of the class istream. It is used to take input from the keyboard.
- printf: printf is a function used to display output on the screen.
- endl: endl is a manipulator used to insert a new line in the output.
- return: return is a keyword used to return a value from a function.
<br>

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

Output: Output when the user inputs "Y" or "y"
```cpp
#include <iostream>

using namespace std;

int main(){
    char answer;
    cout << "Do you like C++? (y/n): ";
    cin >> answer;
    if(answer == 'y' || answer == 'Y'){
        cout << "You like C++" << endl;
        return 0;
    }else{
        cout << "You don't like C++" << endl;
        return 0;
    }
}
```
> Note: The "||" operator is used to check if either of the conditions is true. 

<br>

# Common Exit Codes in C++

- 0: Successful execution
- 1: Unsuccessful execution
- 2: Invalid syntax
<br>etc...

# Common Errors in C++

**Case**: Exit code 2 <br>
Fix: Check the syntax of the program, Make sure that every line ends with a ";" and that every statement is written correctly.

**Case**: Permission denied <br>
Fix: Make sure that there isnt another program with the same name in the same directory is running. If there is, close it and try again.
