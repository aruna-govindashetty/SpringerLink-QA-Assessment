Name: SpringerLinkSearch

Description: To test search function in the SpringerLink 

Setup: Need Visual Studio IDE Community 2017

Nuget packages: 
Specflow: which helps to write test cases in BDD format 
Nunit framework: features a fluent assert syntax, parameterized, generic and theory tests and is user-extensible.
Selenium to perform UI test

Testing the solution: Build the solution and go to Test explorer which displays all the tests Select the test to run ,
right click on the test and say run.

Solution:
Feature file contains test cases in BDD format to test search function
Step definition file contains implementation of the test cases
Pages folder contains properties of the controls in search page

Visual studio + Selenium + Specflow is used in my solution to make the automation process easy and readable.
I have used page object model concept to make the tests generic and efficient and can be used throughout the project.
