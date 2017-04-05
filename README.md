# \<id-datatable\>

Idaho datatable element

## Installation

Add the following to bower.json.

```JSON
{
  "id-datatable": "https://github.com/accessidaho/egov-id-datatable.git"
}
```

## Usage

Import the element:

```html
<link rel="import" href="bower_components/id-datatable/id-datatable.html">
```

Add the element and set properties:

```html
<id-datatable
  data="[[data]]"
  url="/path/to/data"
  columns="[[columns]]"
  buttons="[[buttons]]"
  filename="csvexport"
  basic>
</id-datatable>
```

## Styling

`<id-datatable>` provides the following custom properties for styling:

Key                              | Description                            | Usage/Defaults
---------------------------------|----------------------------------------|--------------------
`--id-primary-color`             | Primary color used for the site        | #2968c0
`--id-link-color`                | Anchor color                           | #0027c1
`--id-link-color-hover`          | Anchor hover color                     | #001875
`--id-primary-light`             | Header active color                    | #d9edf7
`--id-primary-light-border`      | Header border color                    | #eef7fb
