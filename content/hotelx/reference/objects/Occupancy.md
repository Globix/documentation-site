{
  "title": "Occupancy",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int!",
      "name": "id",
      "url": "undefined/scalars/int",
      "description": "Unique ID room in this option.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Pax!]!",
      "name": "paxes",
      "url": "undefined/objects/pax",
      "description": "List of pax of this occupancy.",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "Occupancy",
  "hideGithubLink": true
}
Information about occupancy.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
