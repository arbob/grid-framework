# A Grid based Framework

A Custom 12-Grid based Framework inspired by Bootstrap and SCSS.
- Inbuilt CSS Reset
- Inbuilt Clearfix
- Responsive Design
- 12 Column Grid based Layout
- Customizable and modular
## How to use?

**Size Layout** `size-layout` as _variable_;

- `xs` - Extra Small - Width: 360px
- `sm` - Small - Width: 540px
- `md` - Medium - Width: 720px
- `lg` - Large - Width: 960px
- `xl` - Extra Large - Width: 1140px

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

## Justify and Align Utilities
_JA-Variables Used_ 
- s: start
- e: end
- c: center
- str: stretch
- sa: space-around
- sb: space-between
- 
### Justify Content Utilities
**Syntax**
`.jc-{JA-variable}`

### Justify Items Utilities
**Syntax**
`.ji-{JA-variable}`

### Justify Self Utilities
**Syntax**
`.js-{JA-variable}`

### Align Content Utilities
**Syntax**
`.ac-{JA-variable}`

### Align Items Utilities
**Syntax**
`.ai-{JA-variable}`

### Align Self Utilities
**Syntax**
`.as-{JA-variable}`

### Place Content Utilities
**Syntax**
`.pc-{JA-variable}`

### Place Self Utilities
**Syntax**
`.ps-{JA-variable}`

### Row and Column Gap
> `10px` is default value.

`.r-g { row-gap: 10px; }`

`.c-g { column-gap: 10px; }`

### Border Utilities
**Syntax**
`.border-{variable}`

> `1px solid #aaa` is the default value.

_Variables_ - top, left, right, bottom, `blank` _for all sides_.

**Border Radius**
`.br { border-radius: 5px; }`

### Position Utilities
**Syntax**
`.p-{variable}`

_Variables_ - static, relative, absolute, fixed, sticky.

### Button Component
**Syntax**
`.btn`

### Other Important Utilities

`.ta-c { text-align: center; }`

`.gaf-r { grid-auto-flow: row; }`
`.gaf-c { grid-auto-flow: column; }`

`.fd-r { flex-direction: row; }`
`.fd-c { flex-direction: column; }`

`.fw-r { flex-wrap: row; }`


`.text-bold { font-weight: bold; }`
