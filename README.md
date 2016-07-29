## &lt;md-chip&gt;

Material design: [Chips](https://material.google.com/components/chips.htm)

`<md-chip>` implements the material design chip. The following is the example
of the `<md-chip>` usage

```html
<md-chip label="normal"></md-chip>
<md-chip label="removable chip" removable></md-chip>
```

### Styling

The following custom properties are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--md-chip-background-color` | Background color | `--paper-grey-300` |
| `--md-chip-color` | Foreground color | `--paper-grey-600` |
| `--md-chip-remove-color` | Remove button foreground color | `--paper-grey-500` |
| `--md-chip-background-color-hover` | Hover background color | `--paper-grey-600` |
| `--md-chip-color-hover` | Hover foreground color | `--paper-grey-300` |
| `--md-chip-remove-color-hover` | Remove button hover foreground color | `--paper-grey-300` |

@element md-chip
@blurb A chip material design implementation.
@homepage http://ardf69.github.io/md-chip/
@demo demo/index.html

## &lt;md-contact-chip&gt;

Material design: [Chips](https://material.google.com/components/chips.htm)

`<md-contact-chip>` implements the material design contact chip. The following is the example
of the `<md-contact-chip>` usage

```html
<md-contact-chip label="User" removable selected="0">
    <md-contact-chip-item address="pippo@pippo.com" image="http://pippo.com/face.jpg"></md-contact-chip-item>
    <md-contact-chip-item address="pippo1@pippo.com" image="http://pippo.com/face1.jpg"></md-contact-chip-item>
    <md-contact-chip-item address="+1234567890" image="http://pippo.com/face2.jpg"></md-contact-chip-item>
</md-contact-chip>
```

### Styling

The following custom properties are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--md-contact-chip-background-color` | Background color | `--paper-grey-300` |
| `--md-contact-chip-color` | Foreground color | `--paper-grey-600` |
| `--md-contact-chip-image-color` | The circle background color of the image | `#009587` |
| `--md-contact-chip-letter-color` | The color of the letter for the image | `white` |
| `--md-contact-chip-focused-background-color` | Background focused color | `--paper-grey-300` |
| `--md-contact-chip-focused-color` | Foreground focused color | `--paper-grey-600` |
| `--md-contact-chip-focused-image-color` | The circle background focused color of the image | `#009587` |
| `--md-contact-chip-focused-letter-color` | The focused color of the letter for the image | `white` |
| `--md-contact-chip-pressed-background-color` | Background pressed color | `#d6d6d6` |
| `--md-contact-chip-pressed-color` | Foreground pressed color | `--paper-grey-600` |
| `--md-contact-chip-pressed-image-color` | The circle background pressed color of the image | `#009587` |
| `--md-contact-chip-pressed-letter-color` | The pressed color of the letter for the image | `white` |

@element md-contact-chip
@blurb A chip material design implementation.
@homepage http://ardf69.github.io/md-chip/
@demo demo/index.html

## &lt;md-contact-chip-item&gt;

Material design: [Chips](https://material.google.com/components/chips.htm)

`<md-contact-chip-item>` contains informations about the contact. Example

```html
<md-contact-chip label="User" removable selected="0">
    <md-contact-chip-item address="pippo@pippo.com" image="http://pippo.com/face.jpg"></md-contact-chip-item>
    <md-contact-chip-item address="pippo1@pippo.com" image="http://pippo.com/face1.jpg"></md-contact-chip-item>
    <md-contact-chip-item address="+1234567890" image="http://pippo.com/face2.jpg"></md-contact-chip-item>
</md-contact-chip>
```
### Styling

The following custom properties are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--md-contact-chip-item-background-color` | Background color of the popup list | `white` |
| `--md-contact-chip-item-name-color` | Color of the item name string |`--paper-grey-900` |
| `--md-contact-chip-item-address-color` | Color of the item address string | `--paper-grey-600` |
| `--md-contact-chip-item-image-color` | Background color of the item image | `#009587` |
| `--md-contact-chip-item-letter-color` | The color of the letter for the item image | `white` |
| `--md-contact-chip-item-remove-background-color` | The background color of the remove icon | `#fafafa` |
| `--md-contact-chip-item-remove-color` | The foreground color of the remove icon | `#bbbbbb` |
| `--md-contact-chip-item-focused-background-color` | Background color of the focused popup list | `#e8e8e8` |
| `--md-contact-chip-item-focused-name-color` | Color of the focused item name string | `--paper-grey-900` |
| `--md-contact-chip-item-focused-address-color` | Color of the focused item address string | `--paper-grey-600` |
| `--md-contact-chip-item-focused-image-color` | Background color of the focused item image | `#009587` |
| `--md-contact-chip-item-focused-letter-color` | The color of the letter for the focused item image | `white` |
| `--md-contact-chip-item-focused-remove-background-color` | The background color of the focused remove icon | `#fafafa` |
| `--md-contact-chip-item-focused-remove-color` | The foreground color of the focused remove icon | `#bbbbbb` |
| `--md-contact-chip-item-pressed-background-color` | Background color of the pressed popup list | `#d6d6d6` |
| `--md-contact-chip-item-pressed-name-color` | Color of the pressed item name string | `--paper-grey-900` |
| `--md-contact-chip-item-pressed-address-color` | Color of the pressed item address string | `--paper-grey-600` |
| `--md-contact-chip-item-pressed-image-color` | Background color of the pressed item image | `#009587` |
| `--md-contact-chip-item-pressed-letter-color` | The color of the letter for the pressed item image | `white` |
| `--md-contact-chip-item-pressed-remove-background-color` | The background color of the pressed remove icon | `#fafafa` |
| `--md-contact-chip-item-pressed-remove-color` | The foreground color of the pressed remove icon | `#bbbbbb` |
| `--md-contact-chip-item-selected-background-color` | Background color of the selected popup list | `--paper-cyan-a700` |
| `--md-contact-chip-item-selected-name-color` | Color of the selected item name string | `white` |
| `--md-contact-chip-item-selected-address-color` | Color of the selected item address string | `#b2eaf2` |
| `--md-contact-chip-item-selected-image-color` | Background color of the selected item image | `#009587` |
| `--md-contact-chip-item-selected-letter-color` | The color of the letter for the selected item image | `white` |
| `--md-contact-chip-item-selected-remove-background-color` | The background color of the selected remove icon | `--paper-cyan-a700` |
| `--md-contact-chip-item-selected-remove-color` | The foreground color of the selected remove icon | `#ffffff` |

@element md-contact-chip-item
@blurb A chip material design implementation.
@homepage http://ardf69.github.io/md-chip/
@demo demo/index.html
