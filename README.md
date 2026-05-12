# Lab 7

I worked on this project alone. 

## Questions

Automated tests should be **within a GitHub action whenever code is pushed**. The developer only needs to setup a GitHub action once, and tests are run after each incremental development step, so errors can be caught as soon as they are made.

This choice is better than manually running locally before pushing code, as manually running tests can be tedious and take up a lot of time. 

This choice is also better than running tests after all development is completed, as functions can depend on other functions spanning multiple files, making tracking down the source of failed tests harder. 





