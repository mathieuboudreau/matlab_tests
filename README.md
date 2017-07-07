# Matlab Tests

This repository provides a working example of Matlab's testing framework.

## Supported MATLAB versions

This software has been tested and is known to work with the following versions:

* R2015b (64-bit)

If you experience any compatibility issues, please report them through [GitHub](https://github.com/neuropoly/qMTLab/issues).

## Tests

After installing the software, we suggest that the you evaluate all the test cases for the software. If all tests pass, then
your MATLAB version should be compatible and the software will have completely installed correctly. 

### Run all tests

To run all tests, from MATLAB (assuming you are already in the qMTLab_Tab1s directory), go to the 'test' subfolder

`cd test/`

and execute the following command.

`result = runtests(pwd, 'Recursively', true)`

Any failed test should be resolved prior to starting a workflow.

### Run Test Suite

During development of new features or bug-fixing, it will be preferable to run a test suite relevant to a specific category.
To do so, go to the 'test' folder

`cd test/`

and run the following command:

`result = runTestSuite('Tag')`

substituting `Tag` for one of the following test tags. If you develop new tests and give it a tag which isn't on this list,
please update the README.md file accordingly.

Test tags:

* Unit


## Contributing

Please report any bugs or suggest new features through [GitHub](https://github.com/mathieuboudreau/qMTLab_Tabs/issues).

## About Me

**Mathieu Boudreau** is a PhD Candidate at McGill University in the Department of Biomedical Engineering. He holds a BSc in 
Physics from the Universite de Moncton ('09), and a MSc in Physics from the University of Western Ontario ('11).
