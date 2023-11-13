## Exercise 1
Arrays can be quite confusing. One thing might be access. So lets look at accessing arrays.
```cpp
#include <iostream>

int main(int argC, char* argV[]) {
//Access the first element from the argV Array
  argV[0];
//Access the second element from the argV Array
  argV[1];
//argV Array contains another array in each element of type char
//We can access each char in theses arrays
//For example when running ./myProg Hello World
//The char W can be accessed by getting the second argV element and in this character array the first element
  argV[1][0];
  return 0;
}
```
Rewrite the example so all 3 argV accesses are displayed in the console. You can use `std::cout`
## Exercise 2
Arrays can also be accessed with variables. So we could say `a[0]` then `a[1]` or we could do `int i = 0; for(0…1) a[i]`.
```cpp
int myArray[] = {0, 1, 1, 2, 3, 5};
for() {
  std::cout << myArray[i];
}
``` 
Add the logic in the () of the for loop

## Exercise 3
To come back to argV we can also make arrays in arrays (more dimensionality).
```cpp
int myArray[3][3] = {
 {1, 2, 3},
 {4, 4, 4},
 {5, 6, 7}
}
for() {
 std::cout << MyArray[y][x];
}
```
Add the logic in the () of the for loop

## Exercise 4
To round up our array leanings, lets make something somewhat more difficult.
```cpp
int myPyramid[][]
```
Add the logic in the () of the for loop
## Exercise 5
Another important part is to understand functions.
```cpp
double add(double a, double b) {
  return a + b;
}

int main() {
  std::cout << ;
}
```
Add the numbers 5 and 11 using the function add
## Exercise 6
Functions can have any number of arguments
```cpp
double add(double a, double b) {
  return a + b;
}

double add10(double a) {
 return a + 10.0;
}

std::string chessPos(std::string text, char x, char y) {
 return text + x + y;
}

int main() {
  std::cout << ;
  std::cout << ;
  std::cout << ;
}
```
Use all 3 functions
## Exercise 7
```cpp
int add(int a, int b) {
 return a + b;
}

double add(double a, double b) {
 return a + b;
}

int main() {
  std::cout << ;
  std::cout << ;
}
```
Functions can have the same name and number of arguments but the need to be of a different type. Use both functions.
## Exercise 8

> Written with [StackEdit](https://stackedit.io/).
