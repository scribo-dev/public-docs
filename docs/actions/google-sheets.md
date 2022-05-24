# Google Sheets Action

![Google Sheets Node](assets/google-sheet-node-2.png)

Save some data to a Google Sheet database. 
To use this integration, you will need to first share your sheet with the following e-mail: **scribo@scribo-sheets-integration.iam.gserviceaccount.com** as an editor.

![Google Sheets Share](assets/google-sheet-share.png)

And collect the sheet ID that is located at its URL 

![Google Sheets ID](assets/google-sheet-id.png)

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Sheet ID    | text | Google Sheet ID |
| Values     | object | Values to be saved |

## Outputs

This node has two outputs indicating if the data was saved with success or not.

- Success
- Error