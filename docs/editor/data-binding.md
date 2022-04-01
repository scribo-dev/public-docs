# Data Binding 

When working with dynamic data provided, for example, by the [Data component](components/data) you will need to use the `Data Binding` tab to fill your component's properties.

Let's suppose that your layer tree is the following:

- Data
    - Text

and that the API response is the following

```json
{
    "id": 1,
    "value": {
        "title": "Scribo Data Binding is awesome"
    }
}
```

To display the `title` text on the page, you need to link the response of the API with the `text` property of the `Text` component. 

To do this, all you need to do is click on the `data binding` icon located on the right side of the `text` property field, as shown in the following image:

![Data Binding Button](assets/data-binding-button.png)

It will open a new tab where you can select which property your component should display on the page. In this case, you should choose:

![Data Binding tab](assets/data-binding-tab.png)

- data
    - value
        - title

After selecting, the field will be filed with `${data.value.title}`, indicating that the property is linked to the API response and is not a static string.