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
| `--md-chip-background-color` | Background color | `--paper-grey-300` |
| `--md-chip-color` | Foreground color | `--paper-grey-600` |
| `--md-chip-image-color` | The circle background color of the image | `#009587` |
| `--md-chip-letter-color` | The color of the letter for the image | `white` |
| `--md-chip-focused-background-color` | Background focused color | `--paper-grey-300` |
| `--md-chip-focused-color` | Foreground focused color | `--paper-grey-600` |
| `--md-chip-focused-image-color` | The circle background focused color of the image | `#009587` |
| `--md-chip-focused-letter-color` | The focused color of the letter for the image | `white` |
| `--md-chip-pressed-background-color` | Background pressed color | `#d6d6d6` |
| `--md-chip-pressed-color` | Foreground pressed color | `--paper-grey-600` |
| `--md-chip-pressed-image-color` | The circle background pressed color of the image | `#009587` |
| `--md-chip-pressed-letter-color` | The pressed color of the letter for the image | `white` |
| `--md-contact-background-color` | Background color of the popup list | `white` |
| `--md-contact-name-color` | Color of the item name string |`--paper-grey-900` |
| `--md-contact-address-color` | Color of the item address string | `--paper-grey-600` |
| `--md-contact-image-color` | Background color of the item image | `#009587` |
| `--md-contact-letter-color` | The color of the letter for the item image | `white` |
| `--md-contact-remove-background-color` | The background color of the remove icon | `#fafafa` |
| `--md-contact-remove-color` | The foreground color of the remove icon | `#bbbbbb` |
| `--md-contact-focused-background-color` | Background color of the focused popup list | `#e8e8e8` |
| `--md-contact-focused-name-color` | Color of the focused item name string | `--paper-grey-900` |
| `--md-contact-focused-address-color` | Color of the focused item address string | `--paper-grey-600` |
| `--md-contact-focused-image-color` | Background color of the focused item image | `#009587` |
| `--md-contact-focused-letter-color` | The color of the letter for the focused item image | `white` |
| `--md-contact-focused-remove-background-color` | The background color of the focused remove icon | `#fafafa` |
| `--md-contact-focused-remove-color` | The foreground color of the focused remove icon | `#bbbbbb` |
| `--md-contact-pressed-background-color` | Background color of the pressed popup list | `#d6d6d6` |
| `--md-contact-pressed-name-color` | Color of the pressed item name string | `--paper-grey-900` |
| `--md-contact-pressed-address-color` | Color of the pressed item address string | `--paper-grey-600` |
| `--md-contact-pressed-image-color` | Background color of the pressed item image | `#009587` |
| `--md-contact-pressed-letter-color` | The color of the letter for the pressed item image | `white` |
| `--md-contact-pressed-remove-background-color` | The background color of the pressed remove icon | `#fafafa` |
| `--md-contact-pressed-remove-color` | The foreground color of the pressed remove icon | `#bbbbbb` |
| `--md-contact-selected-background-color` | Background color of the selected popup list | `--paper-cyan-a700` |
| `--md-contact-selected-name-color` | Color of the selected item name string | `white` |
| `--md-contact-selected-address-color` | Color of the selected item address string | `#b2eaf2` |
| `--md-contact-selected-image-color` | Background color of the selected item image | `#009587` |
| `--md-contact-selected-letter-color` | The color of the letter for the selected item image | `white` |
| `--md-contact-selected-remove-background-color` | The background color of the selected remove icon | `--paper-cyan-a700` |
| `--md-contact-selected-remove-color` | The foreground color of the selected remove icon | `#ffffff` |
