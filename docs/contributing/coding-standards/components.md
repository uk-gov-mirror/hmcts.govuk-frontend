# Components

Components must use the `.govuk-` namespace.

For example, `.govuk-button`.

## Writing CSS for components

Components must follow the conventions described in our [CSS coding standards](css.md).

Components must:
* use classes for child elements, scoped to the parent component
* be flexible, not set a width or external padding and margins
* set internal margins in a single direction
* not rely on any other selector outside of the component scss file to style its children

## Testing components on their own
You can run a subset of the test suite that only tests components by running:

    npm run test:components

Note: There's a watch mode that keeps a testing session open waiting for changes that can be used with:

    npm run test:components -- --watch

### Updating component snapshots

If a snapshot test fails, review the difference in the console. If the change is the correct change to make, run:

`npm run test:components -- -u`

This will update the snapshot file. Commit this file separately with a commit message that explains you're updating the snapshot file and an explanation of what caused the change.

## Nunjucks template API
[Read more](nunjucks-api.md) about the way we write component templates.
