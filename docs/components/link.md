---
title: Link Component
description: Link Component specs
---
# Link Component

<iframe width="100%" height="500" src="https://www.youtube.com/embed/Ru7el0Xn7aA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Links can point to internal pages hosted on Scribo or external URL.

## Internal Link

Let's supose that you website has two pages:
- / 
- /blog

To create a link to the `blog` page all you need to do is fill the `Link` property with the relative URL.

| Property | Value   |
| -------- | ------ |
| Text     | Access our blog |
| Link     | /blog |
| Open in new tab     | false |

**It is not recomended to use the full URL in this case**

Using relative URLs in the link property will help Scribo to optimize the user navigation experience. As soon as the link is hovered, the platform will automatically fetch the next page data in order to provide a real time navigation.

## External Link

To create a link to an external website, just fill the link property with the full URL

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Text     | text | Text that will be displayed on the page |
| Link     | text | Destination URL |
| Open in new tab     | checkbox | If the link should be oppened in a new tab or not |