{
  "title": "BookReferenceInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String",
      "name": "client",
      "url": "undefined/scalars/string",
      "description": "The client's reference",
      "args": null
    },
    {
      "typeString": "String",
      "name": "supplier",
      "url": "undefined/scalars/string",
      "description": "The Supplier's reference",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelCancelInput",
      "description": "Cancellation Criteria.",
      "url": "undefined/inputobjects/hotelcancelinput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "BookReferenceInput",
  "hideGithubLink": true
}
Reference object that contains the client reference and/or supplier reference.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
