# cypress-cucumber-typescript
Demonstration of [Issue #61](https://github.com/TheBrainFamily/cypress-cucumber-preprocessor/issues/61) of `cypress-cucumber-preprocessor`

To reproduce:
`npm run test`

1. Press *INTEGRATION TESTS/ts-test/typescript-test.spec.ts*: `add-typescript-to-cypress` should transpile & Cypress execute TypeScript code fine
2. Uncomment line 21 of *cypress/plugins/index.js* & save the change
3. Press *INTEGRATION TESTS/ts-test/typescript-test.spec.ts*: `Error running plugin`
4. Press **Try Again**
5. Press *INTEGRATION TESTS/Facebook.feature*:  `Error running plugin`
6. Press **Try Again**
7. Press *INTEGRATION TESTS/Google.feature*:  `Error running plugin`
