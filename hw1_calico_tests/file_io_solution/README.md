# Homework Assignment 1: File I/O Solution 📝

This repository contains a C++ program for processing data from a CSV file and performing operations specified in an operations file. The program accepts filenames as command-line arguments and uses the provided `test.yaml` file for validation. 📦

## Setup 🛠️

1. **C++ Source Code:**
   - Place your C++ source code file in the same directory as this testing framework and name it `main.cpp`.

2. **Output Data File:**
   - Ensure that your `main.cpp` file outputs to the same data file, as partially mentioned in the homework PDF. 📄

3. **Command-line Arguments:**
   - Confirm that your `main.cpp` file accepts two command-line arguments: the data file and the operations file.

## Running Tests 🚀

To validate your C++ code using the provided test cases in `test.yaml`:

1. **Connect to Calico:**
   - Connect to the Calico Docker environment as previously demonstrated in class.

2. **Navigate to Your Code:**
   - Use the VSCode Ubuntu terminal or your preferred terminal.
   - Navigate to the `file_io_solution` folder where your `main.cpp` file is located using the `cd` command.

3. **Run Tests:**
   - Execute the tests using one of the following commands:
     ```
     calico test.yaml
     ```
     or, for additional debugging information:
     ```
     calico --debug test.yaml
     ```

4. **Check Results Manually:**
   - If you want to see the difference in files you can run: 
     ```
     diff --strip-trailing-cr ./my_solutions/case_1.csv ./solutions/solution_1.csv
     ```
   - Don't forget to change the case number as you need! 🕵️‍♂️

## Test Timeout Adjustment ⏱️

If your code takes longer to solve certain test cases, you can modify `test.yaml` to increase the timeout as needed.

## Contact and Contributions 🤝

If you identify opportunities for improvement or discover issues in the testing framework, please don't hesitate to contact us. Your feedback is essential in helping us enhance the testing quality of this repository.

We encourage contributions to improve this resource. For contribution guidelines, please refer to the repository's issues section. 🙌

---

**Note:** This README provides essential instructions for setting up your project and running tests. Please ensure that your code is correctly validated against the provided test cases. 🚀
