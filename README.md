### BLG223E_ITU_2024_FALL
This repository is designed to assist students in evaluating their code against solutions provided by either myself or fellow contributors. It is important to note that this repository does not facilitate code sharing. Its primary purpose is to offer a straightforward means of verifying code against solution files generated during code execution, with the sole sharing of these files in the format of .csv. We welcome your contributions to enhance this resource. For further guidance, please refer to the README.md files within each respective folder.

###### Homework 1 related info

`Any conclusion you make, taking into account ID, salary and department order, is OK. As long as the information in the line is correct, the characters do not cause any problems.`
- Carriage return characters are not important, as long as it looks same from human eye, it is okay.
  
`Let's assume that there are 10 employees and when you delete the employee whose id is 4, the number of lines in the file becomes 9, while the id of the last employee remains 10. The id number of the newly added employee should be 11. However, what should be noted is that even if the employee with ID 10 is deleted, the ID of the newly added employee will be 11`
- You never assign the id of a deleted employee .

`In the File I/O solution, you can use an array or an extra file as long as you do not save all the data in this data structure. Data read from the file can be kept in a temporary array data structure. However, the results of the last addition, removal and deletion operations should appear in the main file`
- Temporary array usage is okay in file i/o as long as you dont do delete update or add on the array , i guess?

`Question:`  In the array solution, the output file "array_solution.csv" should have the line ID;SALARY;DEPARTMENT or not?,
I guess the line is there in file i/o solution. I ask this because in the homework file 3.1.4 "The number of rows must be the same as the number of rows of the last obtained array."This means that there wont be any header line(I;S;D).
I am asking this just to make sure.

`Answer:Add Id;Salary;Department as the header. However, as you said, due to confusion that may arise because of the sentence in the homework file both solutions will be accepted.`
