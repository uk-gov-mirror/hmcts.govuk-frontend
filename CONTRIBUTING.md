# Contributing

We're not ready for contributions yet, this document exists as a guide for those working on govuk-frontend.

## Code of Conduct
Please read [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) before contributing.

## Running locally

See [running locally](/docs/contributing/running-locally.md).

## Deploying

See [deploying](/docs/contributing/deploying).

## Application architecture

See [application architecture](/docs/contributing/application-architecture.md) for an overview of the directories in this repository.

## Conventions to follow

### Indentation and whitespace

2-space, soft-tabs only. No trailing whitespace.

### CSS

Prefix all classes with `.govuk-`.

Use the BEM naming convention.

For more detail, see our [coding standards for CSS](/docs/coding-standards/css.md) and [testing and linting](/docs/contributing/testing-and-linting.md).

### JavaScript

`govuk-frontend` uses [standardjs](http://standardjs.com/), an opinionated JavaScript linter.
All JavaScript files follow its conventions, and it runs on CI to ensure that new pull requests are in line with them.

For more detail, see our [coding standards for JavaScript](/docs/coding-standards/js.md) and [testing and linting](/docs/contributing/testing-and-linting.md).

If you need polyfills for features that are not yet included in this project, please see the following guide on [how to add polyfills](/docs/contributing/polyfilling.md).

### Components and Nunjucks API

Find components in `src/components`.

See our [coding standards for components](/docs/coding-standards/components.md), [coding standards for Nunjucks macros](/docs/coding-standards/nunjucks-api.md) and [testing and linting](/docs/contributing/testing-and-linting.md).

## Testing and linting

The CI lints SASS and JavaScript, and runs unit and functional tests with Node.

For more detail, see [testing and linting](/docs/contributing/testing-and-linting.md).

## Browser support
Your contribution needs to work with certain browsers as set out in [README](../../README.md). See also [supporting Internet Explorer 8](../installation/supporting-internet-explorer-8.md).

## Application tasks

See [tasks](/docs/contributing/tasks.md).

## Updating Changelog

If you open a GitHub pull request on this repo, please update `CHANGELOG` to reflect your contribution.

Add your entry under `Unreleased` as `Breaking change`, `New feature`, `Fix` or `Internal`.

Please include a description of the work done and a link to the PR (see current `CHANGELOG` for the format).

Include the modified `CHANGELOG` in the PR.


## Versioning

We are not using semantic versioning yet, we are going to talk about this soon.

See `CHANGELOG` for more information.

## Releasing a new version

See [publishing](publishing.md).

## Commit hygiene

Please see our [git style guide](https://github.com/alphagov/styleguides/blob/master/git.md)
which describes how we prefer git history and commit messages to read.
