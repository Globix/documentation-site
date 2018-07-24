{
  "title": "BusinessRulesInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int",
      "name": "optionsQuota",
      "url": "undefined/scalars/int",
      "description": "Options quota per search. Maximum numbers of options to be returned by the search query.",
      "args": null
    },
    {
      "typeString": "BusinessRulesType",
      "name": "businessRulesType",
      "url": "undefined/enums/businessrulestype",
      "description": "Different business rules to filter the returned options.",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelSettingsInput",
      "description": "Settings that you can edit for this avail. Values are loaded by default in our Back Office.",
      "url": "undefined/inputobjects/hotelsettingsinput"
    },
    {
      "name": "SettingsBaseInput",
      "description": "Contains the time out and business rules of a supplier or an access.",
      "url": "undefined/inputobjects/settingsbaseinput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "BusinessRulesInput",
  "hideGithubLink": true
}
List of business rules to use as filter on the options.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
