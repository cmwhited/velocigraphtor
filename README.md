# Velocigraphtor

A GraphQL spec-compliant lib for the [Deno](https://deno.land/) runtime written in TypeScript.

The end-goal is to maintain feature parity with the [graphql.js](https://github.com/graphql/graphql-js) JavaScript reference implementation for GraphQL in the deno runtime.

For more complete documentation on GraphQL, check out [https://graphql.org/](https://graphql.org/).

![Velocigraphtor Logo][./assets/logo/velocigraphtor_logo.png]

## Status

This project was recently began and we are making traction and getting it underway now. Follow the progress here.

## TODO

- [ ] **language** - module for parsing and operating with the GraphQL Query language
- [ ] **types** - module that contains the type definitions exposed by the lib to interact with the GraphQL Schema
- [ ] **validation** - module responsible for validating the GraphQL schema; whether code-first or schema-first
- [ ] **exec** - module handling the execution phase of completing the GraphQL request
- [ ] **errors** - module for creating, formatting, and handling errors that occur while processing the request
- [ ] **util** - module containing common utilities utilized by the other modules
- [ ] **subscription** - module for instantiating and handling data updates
- [ ] **playground?** - perhaps a module to include a GraphQL playground/GraphiQl
- [ ] **examples** - examples and different use-cases.
- [ ] **tests** - there will be comprehensive e2e tests in the `./src/__tests__` directory and each module will contain its own `__tests__` directory for its unit/integration tests

## Issues/Requests

To submit an issue/bug report or to make a request, visit the [issues tracker](https://github.com/cmwhited/velocigraphtor/issues)
