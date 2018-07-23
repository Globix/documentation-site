{
  "title": "HotelBookInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "optionRefId",
      "url": "/travelgatex/reference/scalars/string",
      "description": "Option ID",
      "args": null
    },
    {
      "typeString": "Language",
      "name": "language",
      "url": "/travelgatex/reference/scalars/language",
      "description": "Language to be used in request",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "clientReference",
      "url": "/travelgatex/reference/scalars/string",
      "description": "Booking ID in client's system.",
      "args": null
    },
    {
      "typeString": "DeltaPriceInput",
      "name": "deltaPrice",
      "url": "/travelgatex/reference/inputobjects/deltapriceinput",
      "description": "Indicates price variation permitted by the client.",
      "args": null
    },
    {
      "typeString": "PaymentCardInput",
      "name": "paymentCard",
      "url": "/travelgatex/reference/inputobjects/paymentcardinput",
      "description": "If the payment is done by credit card, it's mandatory to specify the payment type and the credit card information.",
      "args": null
    },
    {
      "typeString": "String",
      "name": "remarks",
      "url": "/travelgatex/reference/scalars/string",
      "description": "Any customer comments for the supplier to consider.",
      "args": null
    },
    {
      "typeString": "HolderInput!",
      "name": "holder",
      "url": "/travelgatex/reference/inputobjects/holderinput",
      "description": "Holder's basic information.",
      "args": null
    },
    {
      "typeString": "[BookRoomInput!]!",
      "name": "rooms",
      "url": "/travelgatex/reference/inputobjects/bookroominput",
      "description": "Rooms within this option.",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "HotelBookInput",
  "hideGithubLink": true
}
Criteria of book.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
