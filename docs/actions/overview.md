# Actions Overview

Some components on our library support user interactions, like:

- Button clicks
- Forms submition
- Form change

Those type of events are handled on Scribo on a workflow style where you can combine multiple action like execute a JS code, navigate to a route, send form data to Google Sheets and much more.

Here is a simple example of a button "On Click" event:

![On Click](assets/on-click-action.png)

## Events Sources

Every component that has an "Actions" property will start with the user event. Some examples are:

- On click → Button Component
- On submit → Form Component

## Actions

Actions define what you want to do when the user execute the corresponding event. There are lots of available actions on the editor. Some are low level, like execute a custom JavaScript code and others are full integration with other services, like save some data to an AirTable database.

Combining action can be a really powerful tool to create complex business logic without any code. The following example illustrates a workflow where if the user that is submitting a form has a company size bigger than 10 members, their data will be stored on a special AirTable Database.

![On Submit](assets/form-action.png)