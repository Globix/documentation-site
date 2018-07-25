{
  "title": "Currency",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "HotelCriteriaSearchInput",
      "description": "Search criteria contains destination, travel dates and the number of pax in each room.\nYou must preload the other fields in our system by complete the fields absents.",
      "url": "/travelgatex/reference/inputobjects/hotelcriteriasearchinput"
    },
    {
      "name": "CriteriaSearch",
      "description": "Search criteria contains destination, travel dates and the number of pax in each room.",
      "url": "/travelgatex/reference/objects/criteriasearch"
    },
    {
      "name": "Price",
      "description": "Price indicates the value of the room/option.\nSupplements and/or surcharges can be included into the price, and will be verified with nodes Supplements/Surcharges.",
      "url": "/travelgatex/reference/objects/price"
    },
    {
      "name": "Priceable",
      "description": "",
      "url": "/travelgatex/reference/interfaces/priceable"
    },
    {
      "name": "Exchange",
      "description": "Provides information about the currency of original, and its rate applied over the results returned by the Supplier.",
      "url": "/travelgatex/reference/objects/exchange"
    },
    {
      "name": "Markup",
      "description": "Informs markup applied over supplier price.",
      "url": "/travelgatex/reference/objects/markup"
    },
    {
      "name": "CancelPenalty",
      "description": "Contains information for cancellation penalities..",
      "url": "/travelgatex/reference/objects/cancelpenalty"
    },
    {
      "name": "CriteriaBookingReferencesInput",
      "description": "Criteria by references",
      "url": "/travelgatex/reference/inputobjects/criteriabookingreferencesinput"
    },
    {
      "name": "DefaultSettingsInput",
      "description": "",
      "url": "/travelgatex/reference/inputobjects/defaultsettingsinput"
    },
    {
      "name": "DefaultSettings",
      "description": "",
      "url": "/travelgatex/reference/objects/defaultsettings"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Currency",
  "hideGithubLink": true
}
The Currenty type represents Currency values. A good example might be a Rate Price Currency.
In queries or mutations, Currency fields have to be specified in ISO 4217 format with enclosing double quotes "EUR".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
