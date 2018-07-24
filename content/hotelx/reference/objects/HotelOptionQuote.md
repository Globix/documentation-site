{
  "title": "HotelOptionQuote",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "optionRefId",
      "url": "undefined/scalars/string",
      "description": "Indicates the valuation key",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "StatusType!",
      "name": "status",
      "url": "undefined/enums/statustype",
      "description": "The possible values in status in response are Available (OK) or On Request (RQ).",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Price!",
      "name": "price",
      "url": "undefined/objects/price",
      "description": "Specifies the prices (Gross, Net and Amount) of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "CancelPolicy!",
      "name": "cancelPolicy",
      "url": "undefined/objects/cancelpolicy",
      "description": "Specifies cancel policies of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "remarks",
      "url": "undefined/scalars/string",
      "description": "Additional information about the option.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Surcharge!]",
      "name": "surcharges",
      "url": "undefined/objects/surcharge",
      "description": "List of surcharges of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[String!]",
      "name": "cardTypes",
      "url": "undefined/scalars/string",
      "description": "List of credit cards",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "AddOns",
      "name": "addOns",
      "url": "undefined/objects/addons",
      "description": "Additional information about the option",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelQuote",
      "description": "",
      "url": "undefined/objects/hotelquote"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "HotelOptionQuote",
  "hideGithubLink": true
}
Contains information about quote(s)
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
