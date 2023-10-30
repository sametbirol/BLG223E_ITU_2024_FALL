<sub>~~When using test_with_error.yaml, don't forget to disable printing a new line after each error. Not found a solution yet!~~</sub>

<sub>Upon thorough testing with [@itu-itis22-saydamm21](https://github.com/itu-itis22-saydamm21), ~~We have identified the issue to be unique to my own setup of environment.~~</sub>

It appears that a particular piece of code was employed by him to mitigate any potential issues arising from newline characters when verifying with Calico. 

To address this, you can include the following line as the first instruction within the main function of your solution:

```cpp
ios_base::sync_with_stdio(false);
```

By doing so, you should encounter no further complications.

You should now be capable of testing with errors while also printing newline characters.

Please remember to utilize `cout` instead of `cerr`

It has been noted that [@itu-itis22-saydamm21](https://github.com/itu-itis22-saydamm21)'s solution employs the `\n` character rather than `endl`

# BLG223E_ITU_2024_FALL 📚

Welcome to the BLG223E course repository for the Fall 2024 semester at ITU. This repository is designed to assist students in evaluating their code against solutions provided by either myself or fellow contributors. 📝

🚫 Please note that this repository does not facilitate code sharing. Its primary purpose is to offer a straightforward means of verifying code against solution files generated during code execution, with the sole sharing of these files in the format of .csv. 📃

We welcome your contributions to enhance this resource. For further guidance, please refer to the README.md files within each respective folder. 🤝

## Homework 1 Related Info 📝
- Carriage return characters are not important, as long as it looks the same from a human eye, it is okay. 🔄

- You never assign the ID of a deleted employee. ❌

- Temporary array usage is okay in file I/O as long as you don't do delete, update, or add on the array, I guess? 🗃️

- Add Id;Salary;Department as the header. However, as you said, due to confusion that may arise because of the sentence in the homework file, both solutions will be accepted. 📋
