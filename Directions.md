# Introduction

Software testing is a crucial part of the devlopment cycle. Every project must be properly tested to ensure it releases in the best possible state. Developers and testers should keep testing in mind from the start of the project. Some basic knowledge of Software Development is required.
________________________________________________________________________________________________
# Steps

### 1) Determine Requirements
+ listen to specifications and needs of the project provided by the client(s)/stakeholder(s).
+ Provide input and get as much clarity as possible for each requirement/idea.
+ Take detailed notes and create diagrams that make these requirements as clear as possible during development.

### 2) Create Test Strategy
**Note:** *Testing should instill confidence in the product's quality, not just test the software.*
+ Create an outline describing the testing approach used in the development cycle
    - Testing strategies should ensure the product is error-free, sustainable, and simple to use.
+ Pay close attention to requirments established in Step 1, highlighting the most important points
+ Determine the environments the program is being developed for
    - Determine all necessary versions of the environments as well, so the tests are as throrough as possible
    - Ex: The progam must be tested in: Windows 7, Windows 10, MacOS Catalina, and MacOS Mojave.
+ Determine all 3rd party software necessary for the program, so compatibility can be tested.

### 3) Plan Tests
+ Determine type of test - Traditional/Manual or Automated.
   - **Note:** *For Manual Testing Skip Step 5, For Automated Testing skip Step 6.*
+ Setup Systems in each environment being tested.

+ Create scenarios to test and determine expected outputs for these scenarios.
    - Scenarios should range from simple and common to diverse and more complex
+ Create testing schedule

### 4) Create exit criteria
+ Establish minimum criteria that must be met before release or before team moves on to the next aspect of project.
    - Rule of thumb: Project has a 90% test pass rate and all critical defects are fixed before release
    - Pass rates may be set lower to move onto another aspect of the project, as each aspect can be fixed further before release.

### 5) Automated Testing
+ Choose testing tools based off of the important requirements highlighted in Step 2 and the scenarios/test cases established in Step 3
+ Create scripts to use with the testing tool
+ Provide the scripts with test inputs, and execute the tests using the chosen tools

### 6) Manual Testing
+ Manually Test different cases and report any ouput that differs from expected/desired results
+ Make sure the program is intuitive and easy for users to use.
+ Types of manual testing
    - **Unit Testing:** Test small parts of the project (unit) before working on the next part
    - **Integration Testing:** Test several units together to make sure they work as a whole
    - **System Testing**: Test the entirety of the project as a whole.
    - **Acceptance Testing**: Test the product for real world use, both internally and with a small external user base (Beta Testing)

### 7) Report Test Results
+ Create a detailed report describing the results of tests and issues that were found
    - Keep the language of the report simple, but still make it as detailed as possible
    - Include screenshots/videos of errors to clearly show the issues
    - Communicate with Developers and track their progress addressing reported errors

### 8) Test Closure
**Note:** *This report formally completes the testing process, stating the project is ready for release*
+ Create a document summarizing all tests conducted.
+ Give a detailed analysis of errors found and fixed.


 



