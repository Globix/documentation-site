{
  "title": "DateTime",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Board",
      "description": "Board type.",
      "url": "/hotelx/reference/objects/board"
    },
    {
      "name": "Category",
      "description": "Category Type",
      "url": "/hotelx/reference/objects/category"
    },
    {
      "name": "Hotel",
      "description": "Hotel Type",
      "url": "/hotelx/reference/objects/hotel"
    },
    {
      "name": "Media",
      "description": "Contains media information.",
      "url": "/hotelx/reference/objects/media"
    },
    {
      "name": "Airport",
      "description": "Airport Type",
      "url": "/hotelx/reference/objects/airport"
    },
    {
      "name": "RoomStatic",
      "description": "Room Type",
      "url": "/hotelx/reference/objects/roomstatic"
    },
    {
      "name": "Destination",
      "description": "Destination Type",
      "url": "/hotelx/reference/objects/destination"
    },
    {
      "name": "AuditData",
      "description": "Data sent and received in the supplier’s native format.",
      "url": "/hotelx/reference/objects/auditdata"
    },
    {
      "name": "Stat",
      "description": "",
      "url": "/hotelx/reference/objects/stat"
    },
    {
      "name": "Transactions",
      "description": "Supplier transaction",
      "url": "/hotelx/reference/objects/transactions"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "DateTime",
  "hideGithubLink": true
}
The DateTime type represents DateTime values. A good example might be a transaction TimeSpan.
In queries or mutations, DateTime fields have to be specified in ISO 8601 format with enclosing double quotes: "2017-10-22T13:57:31.123Z".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
