---
title: Google Tag Manager
description: How to add a Google Tag Manager to your website
---

# Google Tag Manager

![Google Tag Manager Configuration](assets/gtm-config.png)

## How to install

Go to your team's dashboard to add a customizable Google Font for your website.

Dashboard → Team Details → General → Settings → GTM

## GTM Configuration

Scribo's websites are considered Single Page Apps (SPA). This means that you will need to make some configuration changes on the GTM dashboard to make events trackable not only on page load but on browser history change too.

### Create a new Trigger

![Triggers](assets/gtm-triggers.png)

First, you will need to create a new trigger that responds to changes in the browser history, like in the image below:

![Trigger History Change](assets/gtm-trigger-config.png)

### Configure Tag

Now you will add this new trigger to the tags like GA Events. Doing this, you will make sure that all custom events will be sent to Google Analytics during the user navigation.

![Google Analytics Events](assets/gtm-ga-event.png)
