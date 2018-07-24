{
  "title": "BookingCriteriaType",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "HotelCriteriaBookingInput",
      "description": "Criteria of book contains basic information to find a book or books.",
      "url": "undefined/inputobjects/hotelcriteriabookinginput"
    }
  ],
  "enumValues": [
    {
      "name": "DATES",
      "description": "Search by date range",
      "isDeprecated": false,
      "deprecationReason": null
    },
    {
      "name": "REFERENCES",
      "description": "Search by reference codes",
      "isDeprecated": false,
      "deprecationReason": null
    }
  ],
  "operator": "enum",
  "typename": "BookingCriteriaType",
  "hideGithubLink": true
}
Indicates the type of criteria in the request of the booking list
## GraphQL schema definition

{{% graphql-schema-enum %}}

## Required by

{{% graphql-require-by %}}
