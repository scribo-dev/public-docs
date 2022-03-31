# Loop Component

<iframe width="100%" height="500" src="https://www.youtube.com/embed/PRbmqvvCgyk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The `Loop` component should be used when you would like to repeat the same child component. It is really powerfull when combined with the `Data` component.

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Items     | data binding | list of items to repeat |
| Key Property     | data binding | key property, usually the id of the item |

## Example

Let's use the pokemon API to create a list of the first generation of pokemons. First, add a `Data` component to your page with the following properties:

https://pokeapi.co/api/v2/pokemon?limit=150

If you check the result in the network tab, you will see that something like this:

```json
{
    "count": 1126,
    "next": "https://pokeapi.co/api/v2/pokemon?offset=150&limit=150",
    "previous": null,
    "results": [
        {
            "name": "bulbasaur",
            "url": "https://pokeapi.co/api/v2/pokemon/1/"
        },
        {
            "name": "ivysaur",
            "url": "https://pokeapi.co/api/v2/pokemon/2/"
        },
        ...
}
```

The goal is to display the `results` on the page, and to do , you will need the `Loop` component. Add one as the child of the `Data` with the following properties:

| Property | Value   |
| -------- | ------ |
| Items     | ${data.results} |
| Key Property     | name |

And add a `Text` element as a child to the `Loop`. If you open the data binding window to the `text` property, you will see that the `data` object has changed to reflect the result of the `Loop`. Now, instead of the full list of pokemons, you get each item of the list. If you use these properties, you will finally see the list on the page.

| Property | Value   |
| -------- | ------ |
| Text     | ${data.value.name} |