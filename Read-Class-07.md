# Ten Thousand 2

### Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.
In Python, variable scope refers to where a variable is visible and accessible. There are two scopes: local and global.

- Local scope: Variables defined within a function or block are local variables. They are only accessible within that specific function or block and are destroyed when the function or block completes.

- Global scope: Variables defined outside any function or block are global variables. They can be accessed from anywhere within the program, including inside functions or blocks.

In summary, local variables are limited to their specific function or block, while global variables can be accessed from anywhere in the program.

### How do the global and nonlocal keywords work in Python, and in what situations might you use them?

- `global` keyword is used to access and modify global variables from within a local scope (such as a function).

- `nonlocal` keyword is used to access and modify variables from an outer (enclosing) scope, typically within nested functions.

In short, `global` is used to work with global variables inside a local scope, while `nonlocal` is used to work with variables from an outer scope within nested functions.

### In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.

Big O notation is a standardized way to measure and compare the efficiency of algorithms. It helps us understand how an algorithm's performance scales with input size, enabling us to make informed decisions about algorithm selection and optimization. It provides a high-level understanding of an algorithm's efficiency, independent of hardware or implementation details.

### Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.
```
import random

dice_roll = random.randint(1, 6)
To calculate the probability of rolling a specific number, such as 6, over a large number of trials, you can perform multiple iterations and count the number of successful outcomes:

import random

num_trials = 1000000
desired_outcome = 6
successful_trials = sum(1 for _ in range(num_trials) if random.randint(1, 6) == desired_outcome)

probability = successful_trials / num_trials
print(probability)
```
