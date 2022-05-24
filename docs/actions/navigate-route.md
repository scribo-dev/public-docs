# Navigate to Route Action

![On Click](assets/on-click-action.png)

Usually, you would use the [Link](../components/link) component to redirect a user to a new page, but sometimes you need more control of this action. Some examples would be:

- Redirect a user to a specific page after a form submission
- Make an HTTP request on the user's button, click and redirect on the success

![On Submit](assets/form-action.png)

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Route     | select | Select an existing route |
| Full URL     | text | When the route has a dynamic path, define the full URL |