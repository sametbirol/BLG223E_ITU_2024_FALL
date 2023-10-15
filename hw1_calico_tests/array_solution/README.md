Place your C++ source code file in the same directory as this testing framework and name it "main.cpp"
Make sure that your main.cpp file outputs to the same directory as "array_solution.csv" as requested in homework pdf.

Ensure that your "main.cpp" file accepts file names as command-line arguments. Typically, this means that your main function should accept two arguments: the data file and the operations file.

Use the provided test cases in "test.yml" to validate your C++ code. You can run the tests and compare your program's output against the expected output to check for correctness.

To run these test on calico , connect the docker environment preoviously shown in class.

Go to vscode ubuntu terminal that starts with test@vm_docker:~/hostVolume$ 
Go to array_solution folder where your c++ file is(current folder) by cd commands.
run :
    calico test.yaml
or:
    calico --debug test.yaml
for more info.

Don't forget to check the "test_results.txt" file taht will be created after succesfull compares.

Please contact if there are improvements to made or mistakes to fix. Help us improve the testing quality of this repo.
