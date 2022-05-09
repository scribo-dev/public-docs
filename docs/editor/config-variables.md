---
title: Config Variables
description: Editor option for declaring config variables
---
# Config Variables

Often you will need to store a configuration value that will be used in multiple pages of your project, like:

- API URL
- API Tokens
- Contact email

## Create

To avoid duplication by hardcoding those values when needed, you can create a `Config Variable` (Environment Variable) by clicking on the button on the left sidebar and starting a new variable. It should have the following properties:

- key
- label
- type
- value
- description

After creating, those variables will be available in Data Binding fields, at `config.KEY` or on code at `props.config.KEY.`

**Important**: these variables are available to the browser and are public. **Do not store server secrets in Config Variables**

## Different Environments

If your project has GitHub Sync activated, you can create custom config variables for each branch you are working on. By default, every new branch will use the `main` config, but you can edit/create them.

Scribo will copy the variables from `main` to this new branch environment if you choose to edit.
