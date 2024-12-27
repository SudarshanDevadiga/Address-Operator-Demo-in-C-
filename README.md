# Address Operator Demo in C++

A simple C++ program demonstrating the use of the address operator (&) to display memory addresses of variables.

## Description

This program shows how to use the address operator to access and display the memory locations where variables are stored. It's a fundamental demonstration of memory concepts in C++.

### Key Features
- Address operator usage
- Memory address display
- Multiple variable declaration
- Basic pointer concepts

## Code Structure

```cpp
#include<iostream>
using namespace std;

int main()
{
    int var1 = 3;
    int var2 = 24;
    int var3 = 17;
    cout << "Address of var1: "<< &var1 << endl;
    cout << "Address of var2: "<< &var2 << endl;
    cout << "Address of var3: "<< &var3 << endl;
}
