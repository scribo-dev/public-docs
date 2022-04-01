# Properties Panel

![Properties Panel](assets/properties-panel.png)

When you select any component in the [Layers Tree](./editor/layers) the properties panel will be revealed at the right sidebar. It can be separated into 4 sections:

- Conditional Properties
- Component Properties
- Screen size and component state
- Styles

## Component Properties

Each component type has a set of properties. The `Text` component has the `text` prop, and a `Link` is not a link without an URL. All these properties are set in this section of the panel.

## Styles

Here is where you will layout and style your component. This section is separated into eight parts:

- Layout: define visibility, position, and how the element is displayed on the page
- Size: width, height ...
- Spacing: margins, paddings ...
- Position: top, left, bottom, right
- Background: background color and opacity
- Typography: text size, weight, color...
- Border: border-color, size...
- Others

## Screen size and component state

All the styles can be **overwritten** by selecting a specific screen size.

- Base
- Small
- Medium
- Large
- X Large

or a component state like:

- Hover
- Focus

## Conditional Properties

![Conditional Props Code](assets/conditional-props.png)

Like the screen size overwrite functionality, there are some cases where you need to use different properties if a condition is satisfied. This is an advanced feature and requires some coding knowledge.

To create a condition, add a new one by clicking on the select field and typing the condition using the code editor.