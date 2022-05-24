---
title: Select Field Component
description: Select Field Component specs
---
# Select Field Component

![Select Field](assets/select-field.png)

## Properties

The Select Field has the same properties as the [Field](./field) component, with the addition of:

- Options
- Dynamic Options

## Options Property

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Name   | text | Name of the option displayed on the select field |
| Value     | text | Value of the option |

## Dynamic Property

Used when you need to create the option based on other variables available on the page. This property accepts a JavaScript code that should return a list with the following structure:

```js
return [
    {
        "name": "OPTION_NAME",
        "value": "OPTION_VALUE"
    }
]
```