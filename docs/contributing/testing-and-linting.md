# Testing and linting

The CI lints SASS and JavaScript, and runs unit and functional tests with Node.

## Running all tests locally

To check the whole codebase, run:

```
npm test
```

This will trigger [standard](https://github.com/standard/standard) and [sass-lint](https://github.com/sasstools/sass-lint) for linting, and [Jest](https://github.com/facebook/jest) for unit and functional tests.

See [Tasks](tasks.md) for details of what `npm test` does.

## SASS linting

See [CSS Coding Standards](/coding-standards/css.md#formatting-and-linting) for details.

## Javascript linting

See [JavaScript Coding Standards](/coding-standards/js.md#formatting-and-linting) for details.

## Unit and functional tests with Node.js

We use [Jest](https://github.com/facebook/jest) for testing Components (see `[component-name].test.js` inside component directory).

See [Components Coding Standards](/coding-standards/components.md#testing-components-on-their-own) for details.
