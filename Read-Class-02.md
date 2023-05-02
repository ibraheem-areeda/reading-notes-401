# Read: Class 02
## Readings: Testing and Modules
### What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?
1. Increased test coverage: TDD ensures that all parts of the code are covered by tests, which helps to catch bugs early in the development process.

2. Improved code quality: By writing tests first, the developer is forced to think about the design of their code and how it will be used. This can lead to better code quality and more maintainable code.

3. Reduced debugging time: Because bugs are caught early in the development process, TDD can help to reduce the amount of time spent on debugging.

4. Increased confidence: TDD gives the developer confidence that their code works as intended and that it will continue to work as changes are made.

### Explain the purpose of the if __name__ == '__main__': statement in Python scripts. What are some use cases for including this conditional in your code?
The purpose of the if __name__ == '__main__': statement in Python is to ensure that a section of code is only executed when the script is run directly, and not when it is imported as a module. This is commonly used to define a main function or block of code that will only run when the script is executed as the main program. The use cases for including this conditional statement include organizing code into reusable modules, testing and debugging code, and running scripts from the command line.

### Describe the concept of recursion in Python.
In Python, recursion involves a function calling itself with different parameters until a base case is reached, at which point the function returns a result that is then used to solve the previous calls in the stack.

### What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.
- Modules are single Python files that contain functions, classes, and variables.
- Packages are collections of related modules that are organized in a directory structure and can contain sub-packages.
- To create a module, you can simply create a Python file with the desired code.
- To import a module or package, you can use the import statement followed by the module or package name.
- To use functions, classes, or variables from a module or package, you can use the dot notation: module_name.function_name().
- To create a package, you need to create a directory with an __init__.py file, which marks the directory as a package and can contain initialization code for the package.
- To import modules from a package, you can use the dot notation: package_name.module_name.function_name().
- To import all modules from a package, you can use the * wildcard: from package_name import *. However, this is generally discouraged due to potential naming conflicts.
