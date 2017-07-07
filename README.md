# Matlab Tests

This repository provides a working example of MATLAB's testing framework using classes, 
using a very simple function case (sum of two numbers). In order to see how the test would
react under a bug, feel free to change the sumNumbers.m functionality (e.g. make it return
the difference).

Run `startup.m` to ensure that all files in the repository are added to the MATLAB path.

See MATLAB's documentation for more details on their framework: https://www.mathworks.com/help/matlab/matlab_prog/write-simple-test-case-using-classes.html

## Do's and Don'ts of unit testing

### Do

* Create a separate test file for each function/class being tested. 

* Name your tests clearly and consistently .

* Assert a single code feature per test.

### Don't

* Write tests that take a very long time to execute.

* Test multiple code feature in a single test method.


## Tests

To run all tests, from MATLAB (assuming you are already in the qMTLab_Tab1s directory), 
execute the following command.

`result = runtests(pwd, 'Recursively', true)`

### Run Test Suite

During development of new features or bug-fixing, it may be preferable to run a test suite relevant to a specific category.
To do so, run the following command:

`result = runTestSuite('Tag')`

substituting `Tag` for one of the following test tags.

Test tags:

* Unit

## Contributing

Please report any bugs or suggest new features through [GitHub](https://github.com/mathieuboudreau/qMTLab_Tabs/issues).

## About Me

**Mathieu Boudreau** is a PhD Candidate at McGill University in the Department of Biomedical Engineering. He holds a BSc in 
Physics from the Universite de Moncton ('09), and a MSc in Physics from the University of Western Ontario ('11).
