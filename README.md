# graphql-validator-example

This is a test project used to verify the graphql-validator tool

## Installation

Must install project dependencies first

```
npm install
```

## Verification

This project currently contains 2 examples for confirming the validator:

```
npm run test
```
Confirms the examples from the validator README is working

```
npm run example
```
Confirms a more complex query example works

```
npm run invalid
```
Confirms the validator will throw an error if the query doesn't match the schema
