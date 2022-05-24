# Actions Overview

Some components of our library support user interactions, like:

- Button clicks
- Forms submission
- Form change

Those types of events are handled on Scribo in a workflow style where you can combine multiple actions like executing a JS code, navigating to a route, sending form data to Google Sheets, and much more.

Here is a simple example of a button "On Click" event:

![On Click](assets/on-click-action.png)

## Events Sources

Every component with an "Actions" property will start with the user event. Some examples are:

- On click → Button Component
- On submit → Form Component

## Actions

Actions define what you want to do when the user executes the corresponding event. There are lots of available actions on the editor. Some are low-level, like executing a custom JavaScript code and others are full integration with other services, like saving some data to an AirTable database.

Combining action can be a potent tool to create complex business logic without any code. The following example illustrates a workflow where if the user submitting a form has a company size bigger than ten members, their data will be stored on a special AirTable Database.

![On Submit](assets/form-action.png)