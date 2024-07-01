
# BBC Website UI Tests

This project contains automated UI tests for the BBC website using Playwright with JavaScript. It uses playwright test runner to execute the test cases. This is a Data Driven framework focused on separating the test scripts logic and the test data. It is designed with page object model. The test data set is stored in a json file and the test scripts is built to locate the test data in the file for each test. The project has been built on POM model to allow for easy scalability.

## Project Structure

BBCWebsite
│
|── config.js
|── locators/
|── pages/
│   ── BasePage.js
|── tests/
│── data/
    └── loginData.json

## Supported Browsers

1. Desktop Chrome
2. Desktop Firefox
3. Desktop Safari

## Steps to use
1. Installation
Playwright framework requires Node.js v14+ to run.

2. Code from github need to be download OR cloned using git command.
    git clone e.g https://github.com/yourusername/playwright-project.git
    cd playwright-project

3. Installing the dependencies and initialise playwright project
      npm install and  npm init playwright@latest    

4. Execution
 Execute in the terminal= npx playwright test --headed  to run in headed mode
 or npx playwright test

5. Reports
 Execute in the terminal=  npx playwright show-report 
