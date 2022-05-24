---
title: Form Component
description: Form Component specs
---
# Form Component

![Form Example](assets/form.png)

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Initial State     | code | Form initial values |
| Debounce     | number | How often the "OnChange" event should be called. Number in milliseconds |
| Enable Reinitialize     | boolean |  |
| Actions     | action |  |

The `initial state` property is not required, but when needed, it should be in the following structure:

```js
return {
    "FIELD_NAME": "INITIAL_VALUE"
}
```

Where `FIELD_NAME` would be the name of each input, select or checkbox.

## Actions

![Form Actions](assets/form-actions.png)

| Event | Description                       |
| -------- | --------------------------------- |
| On Submit    | Triggered when the user submits the form |
| On Change     | Triggered when any field inside the form changes its value, and the Debounce property is defined |


## Children

The `Form` component should be used as a parent component for the following components:

- [Field](./field)
- [Select Field](./select-field)
- [Text Area](./textarea)
- [Button](./button)

