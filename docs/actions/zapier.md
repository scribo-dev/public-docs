---
title: Zapier Integration
description: How to trigger a Zapier Zap
---
# Zapier Trigger

**Invite Only** please contact our team to help you setting up this integration

Scribo provides a native integration with Zapier. With it you can trigger a zap on, for example, a form submition or a button click.
To configure this integration you will need to:
1. Add the Scribo integration as a Zap Trigger
2. Generate an API Key on Scribo
3. Copy the webhook provided by Zapier
4. Use the Zapier action on a Scribo component

## Scribo Trigger

Every Zap starts with a trigger. To start the integration just search for Scribo in the search bar.

![Zapier New Trigger](assets/zapier-new-trigger.png)

After that you will need to select and event. In this case you need to select

`User Action`

Next you will need to authenticate.

## Configure Auth

When you start with the authentication process, a popup like the bellow will appear.

![Zapier Auth](assets/zapier-auth.png)

The API Key can be generated at our [Dashboard](http://app.scribo.dev/api-keys)

![New API Key](assets/api-key.png)

## Use Action

After authenticating, Zapier will display a webhook URL that you need to copy.

![Zapier Webhook](assets/zapier-webhook.png)

In your Scribo page, you can use, for example, a Form Component and add an Zapier action to the `On Submit` event, like shown bellow:

![Zapier Action](assets/zapier-action.png)

The webhook URL copied on the last step is important here.