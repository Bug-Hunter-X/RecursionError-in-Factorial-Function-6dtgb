This repository contains a simple Python program demonstrating a common error in recursive functions. The `factorial` function is designed to calculate the factorial of a non-negative integer. However, if a negative integer is passed to the function, it will lead to infinite recursion and eventually a `RecursionError`. The `bugSolution.py` file provides a corrected version of the function, which handles negative input gracefully.