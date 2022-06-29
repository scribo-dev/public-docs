---
title: Make.com Integration
description: How to trigger a Make Scenario
---
# Make.com Trigger

<iframe width="100%" height="500" src="https://www.youtube.com/embed/Cojv6ndGMzk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Invite Only** please contact our team to help you set up this integration

Scribo provides a native integration with Make. With it you can trigger a scenario on, for example, a form submition or a button click.
To configure this integration you will need to follow these steps:

## Scribo Trigger

To start the integration just search for Scribo in the search bar.

![Make New Trigger](assets/make-new.png)


Next you will need to authenticate.

## Configure Auth

When you start with the authentication process, a popup like the bellow will appear.

![Make New Webhook](assets/make-webhook-add.png)

Click on the the `Add` button to create a new webhook. A new popup will appear asking for the connection details. Since it is your first time integrating with Make, you will need to create a new Connection by clicking again on the `Add` button.

![Make New Connection](assets/make-webhook.png)

Make will ask you for an API key that can be can be generated at our [Dashboard](http://app.scribo.dev/api-keys)

![Make API Key](assets/make-api-key.png)

## Use Action

After authenticating, Make.com will display a webhook URL that you need to copy.

![Make Webhook URL](assets/make-webhook-url.png)

In your Scribo page, you can use, for example, a Form Component and add an Make.com action to the `On Submit` event, like shown bellow:

![Make.com Action](assets/make-scribo.png)

The webhook URL copied on the last step is important here.