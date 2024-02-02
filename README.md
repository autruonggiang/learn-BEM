# BEM
- The naming standard for writing CSS.

## Meaning:
- Abbreviation for: Block Element Modifier.
    + Block: Container.
    + Element: Component within the container.
    + Modifier: Adds meaning to a Block or Element.

## Why use BEM?
- Consistency in naming conventions.
- Avoids conflicts when multiple developers work on the same project.

- Prevents CSS styles from being overridden by others.

## Syntax
- .block
- .block__element

- .block--modifier
- .block__element--modifier

## Applications
- Building website layouts.
- Constructing components on a website.

## Advantages
- Clear and consistent naming.
- Easy reusability of code.
- Facilitates collaboration within a team.
- Encourages a modular approach, reducing the risk of style conflicts.

## Disadvantages
- Longer class names.
- Some find it visually unappealing.

## When is BEM suitable?
- Large projects with multiple team members.
- Projects with numerous pages or a high number of interface components.

## Practical examples
- Creating a button.
    + Enabled: Pointer, hover effect.
    + Disabled: Arrow, no effect.
- Designing a message.
- Developing a component for a website.

## Nested Blocks in BEM
In cases where a Block contains another Block:

- The child Block serves as a shared component.
- The child Block contains multiple elements.

## References
- https://codepen.io/ng-ngc-sn-the-bashful/pen/VwKXNyK
- https://codepen.io/ng-ngc-sn-the-bashful/pen/Exgmxqp