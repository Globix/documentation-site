{
  "title": "CriteriaSearch",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Date!",
      "name": "checkIn",
      "url": "undefined/scalars/date",
      "description": "Check-in date for booking\nFormat: YYYY-MM-DD",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Date!",
      "name": "checkOut",
      "url": "undefined/scalars/date",
      "description": "Check-out, booking date\nFormat: YYYY-MM-DD",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[String!]!",
      "name": "hotels",
      "url": "undefined/scalars/string",
      "description": "Contains the list of hotels's ID",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[RoomCriteria!]!",
      "name": "occupancies",
      "url": "undefined/objects/roomcriteria",
      "description": "For multi-room bookings, this array will contain multiple elements (rooms).\nFor each room you have to specify its own occupancy.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Language",
      "name": "language",
      "url": "undefined/scalars/language",
      "description": "Language to be used in request",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Currency",
      "name": "currency",
      "url": "undefined/scalars/currency",
      "description": "Currency requested if supported by supplier",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Country",
      "name": "nationality",
      "url": "undefined/scalars/country",
      "description": "Nationality of the guest (use ISO3166_1_alfa_2)",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "market",
      "url": "undefined/scalars/string",
      "description": "Targeted zone, country or point-ofsale-to be used in request.",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelSearch",
      "description": "Results from Avail Hotel; contains all the available options for a given date and itinerary",
      "url": "undefined/objects/hotelsearch"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "CriteriaSearch",
  "hideGithubLink": true
}
Search criteria contains destination, travel dates and the number of pax in each room.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
