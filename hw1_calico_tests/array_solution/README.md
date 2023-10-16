# Homework Assignment 1: Array Solution

This repository contains a C++ program for processing data from a CSV file (`array_solution.csv`) based on operations specified in an operations file. The program accepts filenames as command-line arguments and uses the provided `test.yaml` file for validation.

## Setup

1. **Place Your C++ File:**
   - Place your `main.cpp` file in the same directory as this testing framework.

2. **File Naming:**
   - Name your C++ source code file as `main.cpp`.
   - Ensure that your `main.cpp` file outputs to the same directory as `array_solution.csv` as requested in the homework PDF.

3. **Command-line Arguments:**
   - Ensure your `main.cpp` file accepts two command-line arguments: the data file and the operations file.

## Running Tests

To run tests using the provided test cases in `test.yaml`:

1. **Connect to Calico:**
   - Connect to the Calico Docker environment as demonstrated in class.

2. **Navigate to Your Code:**
   - Use the VSCode Ubuntu terminal or any other preferred terminal.
   - Navigate to the `array_solution` folder where your `main.cpp` file is located..

3. **Run Tests:**
   - Run the tests using the following command:
     ```
     calico test.yaml
     ```
     or, for debugging information:
     ```
     calico --debug test.yaml
     ```

4. **Check Results Manually:**
   - If you want to see differnece in files you can run: 
     ```
     diff --strip-trailing-cr ./my_solutions/case_1.csv ./solutions/solution_1.csv
     ```
   - Don't forget to change the case number as you need!

## Contact and Contributions

If you have suggestions for improvements or if you find any mistakes in the testing framework, please don't hesitate to contact us. Your feedback is invaluable and helps us enhance the testing quality of this repository.

We welcome your contributions to improve this resource. Please follow the guidelines mentioned in the repository's issues section to contribute effectively.

---

**Note:** This README provides essential instructions for setting up your project and running tests. Make sure to follow the guidelines to ensure your code is correctly validated against the provided test cases.
