---
title: Screen Sizes
description: How to test your app on multiple devices and screen sizes
---
# Devices and screen sizes

![Devices](assets/devices.png)

Right from the editor, you can preview your page on multiple devices. At the center top of the editor, you will find four icons indicating the window size of the preview. Each device corresponds to the following screen sizes:

| Device | Property Name   |Screen width   |
| -------- | ------ | ------ |
| Small Screen     | sm | 400 pixels |
| Medium Screen     | md | 800 pixels |
| Large Screen     | lg | 1100 pixels |
| Extra Large Screen     | xl | 1920 pixels |

## Style for device

![Breakpoint Selector](assets/breakpoints-selector.png)

If you select any component on the page, you will be able to change its styles at the right sidebar, like background, typography, position, and many more properties. If you come from a web development background, it is where you will edit the CSS of the component.

One crucial element of this sidebar is the screen size selector or breakpoints. It starts with a value of `Base`. As implied by its name, all properties defined in this state will be applied to all screen sizes. Suppose you change this selection to, for example, `Medium`. In that case, you will notice that all values previously defined will disappear, a

## Properties

Every component on the page will have access to a property called `breakpoints` with the following structure:

```json
"breakpoints": {
    "sm": false,
    "md": false,
    "lg": false,
    "xl": false,
}
```
**Important**: Scribo uses a **mobile-first** approach. This means that each of the `breakpoints` property flags will turn true as soon as the screen size limit is reached. For example:

- If `md` is true, it means that the screen size is equal to or higher than 800 pixels
- If `md` is false, you might be working on mobile screen size.


### Mobile Example
```json
"breakpoints": {
    "sm": true,
    "md": false,
    "lg": false,
    "xl": false,
}
```

### Notebook Example
```json
"breakpoints": {
    "sm": true,
    "md": true,
    "lg": true,
    "xl": false,
}
```

### Large screen Example
```json
"breakpoints": {
    "sm": true,
    "md": true,
    "lg": true,
    "xl": true,
}
```