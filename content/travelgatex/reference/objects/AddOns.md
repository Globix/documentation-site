{
  "title": "AddOns",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "JSON",
      "name": "distribute",
      "url": "undefined/scalars/json",
      "description": "Extra information from the distribution layer",
      "isDeprecated": true,
      "args": null,
      "deprecationReason": "You can find it in distribution AddOn",
      "descriptionSplitted": {
        "date": "2018-05-21",
        "first": "deprecated from",
        "second": "You can find it in distribution AddOn"
      },
      "deprecationDate": "2018-05-21",
      "typeName": "AddOns"
    },
    {
      "typeString": "[AddOn!]",
      "name": "distribution",
      "url": "undefined/objects/addon",
      "description": "Extra information from the distribution layer",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelOptionSearch",
      "description": "An option includes hotel information, meal plan, total price, conditions and room description",
      "url": "undefined/objects/hoteloptionsearch"
    },
    {
      "name": "HotelOptionQuote",
      "description": "Contains information about quote(s)",
      "url": "undefined/objects/hoteloptionquote"
    },
    {
      "name": "HotelBookingDetail",
      "description": "Contains information about booking",
      "url": "undefined/objects/hotelbookingdetail"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "AddOns",
  "hideGithubLink": true
}
Additional information about the option
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
