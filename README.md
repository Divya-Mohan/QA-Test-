# QA-Test-
Automating the user account registraion process 


Objective: To implement happy path test scenario for the user registration process for the given url using Page Object model.
Project Structure
The test project is set up as a unit test project on Visual Studio 2017 using Specflow testing framework and selenium webdriver.
Specflow and selenium are added through nuget package reference for the solution. 
The project has three subfolders, namely
•	Features – This folder contains spec flow feature file describing the happy path scenario for the registration process
•	Steps – This folder contains step definition generated from the feature file.
•	Pages – This folder contains a registration page class. This class considers the registration page as a page and the locators
(web elements) as objects and the user actions as methods , thus  forming a page object model
The project build fine. But the test will not pass. In order to execute test, open test explore and run the selected test. 
Test result folder will be created in the location where the solution is saved. But at the moment it does not output anything.
 
 NB:
I did have trouble in getting spec flow work with the version of visual studio (community version) I installed in my pc.
The project builds fine, but the test fails. I didn’t get enough time to trouble shoot and investigate further into it. 
I’ll be happy to discuss that during the interview.
