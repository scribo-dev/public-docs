---
title: Data Component
description: Data Component specs
---
# Data Component

<iframe width="100%" height="500" src="https://www.youtube.com/embed/K8Ag2Kc5ImQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The `Data` component is used for requesting dynamic content from an API. This information will be available to all of it's child components through databinding  or the `props.data` object.

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| URL     | text | URL of the API |
| Method     | select | HTTP request method: GET or POST |
| Headers     | code | HTTP request headers |
| Body     | code | HTTP request body if method is POST |
| Proxy     | checkbox | If checked, the HTTP request will be made by our server. Useful for avoiding CORS errors |
| Refresh Interval     | text | Interval in which the request should be remade. Useful for pooling data and always displaying the most recent information  |
| Data Transformation     | code | code to manipulate the information returned by the API |

## Exported Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| dataLoading     | boolean | Boolean indicating if the data has already been loaded or not |
| dataError     | Object | Error message when the HTTP request was not completed with success |
| dataRefresh     | function | use this function when you want to refresh the current HTTP request |
