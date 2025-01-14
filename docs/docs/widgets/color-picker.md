---
id: color-picker
title: Color Picker
---

# Color Picker

Color Picker widget is used to select the desired color from the color picker

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Color Picker](/img/widgets/color-picker/colorpickerpopup.png)

</div>

## Properties

### Default Color

The data needs to be an valid hex color
- One can change default color either from color picker or using fx (need to provide only respective hex value)

**Example:**

```json
Valid color : #000000 or #000
Invalid Color : #0000, "black" , rgb(0,0,0) ,
```

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Color Picker](/img/widgets/color-picker/colorpickerdefaultvalue.png)

</div>


## Layout

| Layout          | description                               | Expected value                                                                                                |
| --------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Show on desktop | Toggle on or off to display desktop view. | You can programmatically determining the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}` |
| Show on mobile  | Toggle on or off to display mobile view.  | You can programmatically determining the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}` |

## Styles

| Style      | Description                                                                                                                                                                                                                                              |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Visibility | Toggle on or off to control the visibility of the widget. You can programmatically change its value by clicking on the `Fx` button next to it. If `{{false}}` the widget will not visible after the app is deployed. By default, it's set to `{{true}}`. |

:::info
Any property having `Fx` button next to its field can be **programmatically configured**.
:::

## Example: Selecting/changing color from the color picker and getting respectibe hex, rgb and rgba value of selected color
- Let's start by creating a new app and then dragging the Color Picker  widget onto the canvas.
- Click on the Color Picker widget, a picker pop-up will appear, one can select desired color from the picker.
- In order to close the appeared picker pop-up, one need's to move away mouse from the picker pop-up and picker pop-up will fade away.
- In the Inspector, inside component, look for colorpicker, where one can get respective hex, rgb and rgba color

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Color Picker](/img/widgets/color-picker/colorpickerinspector.png)

</div>
