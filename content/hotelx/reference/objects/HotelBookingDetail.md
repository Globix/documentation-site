{
  "title": "HotelBookingDetail",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Reference!",
      "name": "reference",
      "url": "undefined/objects/reference",
      "description": "Booking ID in the Supplier's system",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Holder",
      "name": "holder",
      "url": "undefined/objects/holder",
      "description": "Holder's name and surname",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "BookingHotel",
      "name": "hotel",
      "url": "undefined/objects/bookinghotel",
      "description": "Information about the hotel.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Price",
      "name": "price",
      "url": "undefined/objects/price",
      "description": "Specifies the prices (Gross, Net and Amount) of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "CancelPolicy",
      "name": "cancelPolicy",
      "url": "undefined/objects/cancelpolicy",
      "description": "Specifies cancel policies of the book returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "remarks",
      "url": "undefined/scalars/string",
      "description": "Additional information about the book.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "BookStatusType!",
      "name": "status",
      "url": "undefined/enums/bookstatustype",
      "description": "Booking Status.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "payable",
      "url": "undefined/scalars/string",
      "description": "Payable.",
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
      "name": "HotelBookPayload",
      "description": "",
      "url": "undefined/objects/hotelbookpayload"
    },
    {
      "name": "HotelCancelDetail",
      "description": "Contains information about cancel",
      "url": "undefined/objects/hotelcanceldetail"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "HotelBookingDetail",
  "hideGithubLink": true
}
Contains information about booking
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
