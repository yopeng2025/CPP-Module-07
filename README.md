# CPP Module 07

## Tech Stack
- C++: A high-level programming language that is widely used for various applications, from system/software development to game programming.
- Git: A version control system to manage source code history.
- GitHub: A platform for hosting and sharing code repositories.

## Compilation
To compile the exercises in this module, you can use the following command in your terminal:

```bash
g++ -o output_file_name source_file.cpp
```

Replace `output_file_name` with your desired executable name and `source_file.cpp` with the name of the source file you want to compile.

Run the executable using:

```bash
./output_file_name
```

## Exercises
### Exercise 1: Explanation of Exercise 1
This exercise demonstrates...

#### Code Example:
```cpp
// C++ code snippet for Exercise 1
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

### Exercise 2: Explanation of Exercise 2
This exercise covers...

#### Code Example:
```cpp
// C++ code snippet for Exercise 2
#include <vector>
#include <iostream>

int main() {
    std::vector<int> numbers = {1, 2, 3, 4, 5};
    for(int num : numbers) {
        std::cout << num << " ";
    }
    return 0;
}
```

### Exercise 3: Explanation of Exercise 3
In this exercise, we...

#### Code Example:
```cpp
// C++ code snippet for Exercise 3
#include <string>
#include <iostream>

int main() {
    std::string name;
    std::cout << "Enter your name: ";
    std::cin >> name;
    std::cout << "Hello, " << name << "!" << std::endl;
    return 0;
}
```

### Additional Notes
Ensure to install a C++ compiler and set up your environment correctly for smooth compilation and execution of the exercises.