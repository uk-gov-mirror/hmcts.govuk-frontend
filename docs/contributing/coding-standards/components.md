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

## Nunjucks template API
[Read more](nunjucks-api.md) about the way we write component templates.
