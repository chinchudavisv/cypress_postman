- Scenario 1 and 2: Implemented using Cypress.
- Scenario 3: Implemented using Postman.

Steps to View the Results:
1. Extract the attached file.
2. Open a terminal in the extracted folder.
3. Run the following commands:
   
- Install dependencies: npm ci
   
- Run Cypress tests & Generate machine readable result file: npm run cypress:run:report
        This will execute the tests, display human-readable results in the console, and generate an XML results file      in the root directory.
      
 - Run Postman tests: npm run postman:run