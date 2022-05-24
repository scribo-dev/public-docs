# AirTable Action

![AirTable Node](assets/airtable-node-2.png)

Save some data to an AirTable database. For this integration to work, you will need to collect some information:

- API Key: can be generated using the following [tutorial](https://support.airtable.com/hc/en-us/articles/219046777-How-do-I-get-my-API-key-)
- Workspace ID: in included on your database URL
![AirTable Workspace ID](assets/airtable-workspace-id.png)
- Table: is your database table name

## Properties

| Property | Type   | Description                       |
| -------- | ------ | --------------------------------- |
| Api Key     | text | AirTable API Key |
| Workspace ID     | text | AirTable workspace id |
| Table    | text | AirTable database table name |
| Values     | object | Values to be saved |

## Outputs

This node has two outputs indicating if the data was saved with success or not.

- Success
- Error