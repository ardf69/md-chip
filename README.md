##&lt;md-chip&gt;

Material design: [Chips](https://material.google.com/components/chips.htm)

`<md-chip>` implements the material design chip. The following is the example
of the `<md-chip>` usage

```html
<md-chip label="normal"></md-chip>
<md-chip label="removable chip" removable></md-chip>
<md-chip checkable label="checkable chip"></md-chip>
<md-chip checkable checked label="checkable chip checked"></md-chip>
```

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--md-chip-background-color` | Default background color | `--divider-color` |
| `--md-chip-color` | Default foreground color | `--secondary-text-color` |
| `--md-chip-background-color-hover` | Hover background color | `--secondary-text-color` |
| `--md-chip-color-hover` | Hover foreground color | `--primary-background-color` |
| `--md-chip-background-color-checked` | Chip checked background color | `--paper-cyan-500` |
| `--md-chip-color-checked` | Chip checked foreground color | `white` |
