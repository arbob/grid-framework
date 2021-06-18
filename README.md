# A Grid based Framework

A custom bootstrap based framework.
- Inbuilt CSS Reset
- Inbuilt Clearfix
- Responsive Design
- 12 Column Grid based Layout
- Customizable and modular
## How to use?

**Size Layout** `size-layout` as _variable_;

`xs` - Extra Small - Width: 360px
`sm` - Small - Width: 540px
`md` - Medium - Width: 720px
`lg` - Large - Width: 960px
`xl` - Extra Large - Width: 1140px

### Container Layout
`1fr` based grid to encompass rows and columns. This is the base section for any `section` and `div`.

**Usage**
`.container-{size-layout}` as an HTML class.

### Row Layout
`1fr * 12` based grid to encompass columns. Divided into 12 columns.

**Usage**
`.row-{size-layout}` as an child class.

### Column Layout
_Variable_ - `$span: 1 to 12;`

**Usage**
- `.col-{span}` as a subclass for `grid-column: span {1 to 12}`.
> E.g. `col-md-4` spans for 4 grid sections and responsive with medium sized screens and onwards.

- `.col-{size-layout}-{span}` for responsive layouts.

### Display Utilities
_Variable_ - `$display: none, inline, block, inline-block, flex, grid;`

**Usage**
`.d-{$display}` as subclass for rows and columns.
> E.g. `.d-flex` will implement `display: flex;`.

### Float Utilities
`.float-left { float: left; }`

`.float-right { float: right; }`

## Justify Utilities
### Justify Content Utilities

