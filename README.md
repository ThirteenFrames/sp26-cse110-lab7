# Lab 7

I worked on this project alone. 

## Questions

### Where would you fit your automated tests in your Recipe project development pipeline? 

Automated tests should be **within a GitHub action whenever code is pushed**. The developer only needs to setup a GitHub action once, and tests are run after each incremental development step, so errors can be caught as soon as they are made.

This choice is better than manually running locally before pushing code, as manually running tests can be tedious and take up a lot of time. 

This choice is also better than running tests after all development is completed, as functions can depend on other functions spanning multiple files, making tracking down the source of failed tests harder. 

### Would you use an end to end test to check if a function is returning the correct output? 

No, as E2E tests are meant to test the entire workflow and simulate what users would actually do. 

Checking if a function is returning the correct output is a very small part of the entire workflow, and a user would definitely do more than just call one function. 
A real user may not even have direct access to call the function. 

A unit test would be more appropriate in this case. 






