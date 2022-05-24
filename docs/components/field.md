---
title: Field Component
description: Field Component specs
---
# Field Component

Main text field of a form.

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Type     | select | text, number, date, or e-mail |
| Input name     | text | Name of the form field |
| Placeholder     | text | Text to show when the field has no value |
| Disabled     | boolean |  |
| Disable Browser Autocomplete     | boolean |  |

## Mask

![Field Mask](assets/field-mask.png)

Field inputs can have masks to improve your form's UX. Some masks examples:

- Phone number: `+00 (00) 00000-0000`

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Mask     | text[] | mask template |

## Validations

![Field Validation](assets/field-validation.png)

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Validation     | select | e-mail, URL, string, or custom |
| Message     | text | Error message |
| Required     | boolean | If the field is required |
| Required Message     | text | Required error message |

The `string` validation has an additional prop

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Match     | regex | Regex to validate the input value |

The `Custom` validation has an additional prop

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Custom Validation     | code | JS code to validate the input value|