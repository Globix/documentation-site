{
  "title": "ConnectUser",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "code",
      "url": "/travelgatex/reference/scalars/string",
      "description": "Unique connected user of a supplier",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "isActive",
      "url": "/travelgatex/reference/scalars/boolean",
      "description": "Indicates whether a connected user is active",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[ConnectUserGroup!]",
      "name": "connectUserGroups",
      "url": "/travelgatex/reference/objects/connectusergroup",
      "description": "Connected user's related data based on its groups",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "ConnectUser",
  "hideGithubLink": true
}
Data related to a connected user and its groups
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
