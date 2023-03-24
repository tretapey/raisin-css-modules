# Custom Grid System

This grid module is a customizable, mobile-first, responsive CSS grid utility built with SCSS.

## Grid Container Classes

- `.grid`: Sets the `display` property to `grid`.

### Columns and Rows

- `.grid-cols-{n}`: Sets the `grid-template-columns` property to a `{n}` column layout, where `{n}` is a number from 1 to 12.
- `.grid-rows-{n}`: Sets the `grid-template-rows` property to a `{n}` row layout, where `{n}` is a number from 1 to 12.

### Gaps

- `.col-gap-{value}`: Sets the `column-gap` property to the specified `{value}`.
- `.row-gap-{value}`: Sets the `row-gap` property to the specified `{value}`.
- `.grid-gap-{value}`: Sets both the `column-gap` and `row-gap` properties to the specified `{value}`.

Gap values: `0` (0rem), `1` (0.25rem), `2` (0.5rem), `3` (0.75rem), `4` (1rem), `5` (1.25rem), `6` (1.5rem), `7` (1.75rem), `8` (2rem).

### Alignment and Justification

- `.align-items-{value}`: Sets the `align-items` property to the specified `{value}`.
- `.justify-items-{value}`: Sets the `justify-items` property to the specified `{value}`.
- `.align-content-{value}`: Sets the `align-content` property to the specified `{value}`.
- `.justify-content-{value}`: Sets the `justify-content` property to the specified `{value}`.

Alignment and justification values: `start`, `end`, `center`, `baseline`, `stretch`.

## Grid Child Classes

- `.col-start-{n}`: Sets the `grid-column-start` property to the specified `{n}`, where `{n}` is a number from 1 to 12.
- `.row-start-{n}`: Sets the `grid-row-start` property to the specified `{n}`, where `{n}` is a number from 1 to 12.
- `.col-end-{n}`: Sets the `grid-column-end` property to the specified `{n}`, where `{n}` is a number from 1 to 12.
- `.row-end-{n}`: Sets the `grid-row-end` property to the specified `{n}`, where `{n}` is a number from 1 to 12.
- `.align-self-{value}`: Sets the `align-self` property to the specified `{value}`.
- `.justify-self-{value}`: Sets the `justify-self` property to the specified `{value}`.

Alignment and justification values: `start`, `end`, `center`, `baseline`, `stretch`.

## Breakpoints

- `sm`: 576px and up
- `md`: 768px and up
- `lg`: 992px and up
- `xl`: 1200px and up

To make a class responsive, simply add the `@{breakpoint}` suffix to the class name. For example, `.grid-cols-3@md` would set the `grid-template-columns` property to a 3-column layout for screens with a width of 768px and up.
