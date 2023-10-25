~~When using test_with_error.yaml, don't forget to disable printing a new line after each error. Not found a solution yet!~~

Upon thorough testing with [@itu-itis22-saydamm21](https://github.com/itu-itis22-saydamm21), We have identified the issue to be unique to my own setup of environment.

You should now be capable of testing with errors.

Please remember to utilize 'cout' instead of 'cerr.' 

It has been noted that [@itu-itis22-saydamm21](https://github.com/itu-itis22-saydamm21)'s solution employs the '\n' character rather than 'endl.'

# BLG223E_ITU_2024_FALL 📚

Welcome to the BLG223E course repository for the Fall 2024 semester at ITU. This repository is designed to assist students in evaluating their code against solutions provided by either myself or fellow contributors. 📝

🚫 Please note that this repository does not facilitate code sharing. Its primary purpose is to offer a straightforward means of verifying code against solution files generated during code execution, with the sole sharing of these files in the format of .csv. 📃

We welcome your contributions to enhance this resource. For further guidance, please refer to the README.md files within each respective folder. 🤝

## Homework 1 Related Info 📝
> Any conclusion you make, taking into account ID, salary, and department order, is OK. As long as the information in the line is correct, the characters do not cause any problems. ✅

- Carriage return characters are not important, as long as it looks the same from a human eye, it is okay. 🔄

> Let's assume that there are 10 employees and when you delete the employee whose ID is 4, the number of lines in the file becomes 9, while the ID of the last employee remains 10. The ID number of the newly added employee should be 11. However, what should be noted is that even if the employee with ID 10 is deleted, the ID of the newly added employee will be 11. 🔢

- You never assign the ID of a deleted employee. ❌

> In the File I/O solution, you can use an array or an extra file as long as you do not save all the data in this data structure. Data read from the file can be kept in a temporary array data structure. However, the results of the last addition, removal, and deletion operations should appear in the main file. 📄

- Temporary array usage is okay in file I/O as long as you don't do delete, update, or add on the array, I guess? 🗃️

**Question:** In the array solution, should the output file "array_solution.csv" have the line ID;SALARY;DEPARTMENT, or not? I guess the line is there in file I/O solution. I ask this because in the homework file 3.1.4 "The number of rows must be the same as the number of rows of the last obtained array." This means that there won't be any header line (ID;SALARY;DEPARTMENT). I am asking this just to make sure. 🤔

**Answer:** Add Id;Salary;Department as the header. However, as you said, due to confusion that may arise because of the sentence in the homework file, both solutions will be accepted. 📋
