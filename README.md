# Cypress exercise

Rename the .example.env file to .env file.

## Execution Steps:
To run the complete suite in headless mode, use the command:
``` npx cypress run ```

To run the individual test in headless mode, use the command:
``` npx cypress run --spec cypress/e2e/loginPage.cy.js (spec filename) ```

To execute in GUI, run the command
``` npx cypress open ``` and select the browser, and click on spec filename to run the specific test.

Screenshots:
1) If ``` npx cypress run``` is used, upon an error- screenshot will get saved automatically under screenshots folder (auto-generated)
2) For manual step- add .cy.screenshot() to test.

For Scenario: Bonus test case 5- clicking on social icons opens page in new tab. Cypress currently doesn't support multiple tabs- https://docs.cypress.io/guides/references/trade-offs#Multiple-tabs

Bugs: <br>
1. lastName input is disabled for error_user <br>
2. Finish button is disabled for error_user

