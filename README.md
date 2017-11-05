# Airtame Kittens API

## Url

http://my-json-server.typicode.com/airtame/kittens/

## Endpoints

### GET `/kittens`

Gets a list of all existing kittens.

### GET `/kittens/:id`

Gets a kitten based on its `id`.

### Basic Options for all endpoints

*Note: All options are optional*

| **Name** | **Values** | **Description**            | **Default** |
|----------|------------|----------------------------|---------------|
| name     | *string*   | The name of a kitten       | `null`        |
| _page    | *number*   | Results page               | 1             |
| _limit   | *number*   | Number of results per page | 10            |

For a full list of options, please check https://github.com/typicode/json-server
