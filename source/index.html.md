---
title: Constellation Brands API Catalog

/*language_tabs:
  - shell
  - ruby
  - python
  - javascript*/

toc_footers:
  - <a href='#'>Sign up for an API Key</a>
  - <a href='https://github.com/tripit/slate'>Powered by Slate</a>
  - <p>&copy; Constellation Brands, Inc. 2017</p>

includes:
  - worker
  - errors

search: true
---

# Constellation Brands API Catalog

Constellation Brands APIs provide instant access to a variety of datasets including Items, Brands, and Worker Demographics. Explore the available APIs to see setup instructions and sample responses.

# Getting Started

Visit the [developer portal](https://anypoint.mulesoft.com/apiplatform/cbrands/#/portals) to request an API key.

<aside class="notice">
You must create an Anypoint Platform account (free) in order to request API access.
</aside>

##Accessing an API Directly

```shell
curl "https://mocksvc.mulesoft.com/what/is/the/url/1.0/items/1002"
  -H "Authorization: YourAPIKey"
```

> The above command returns the following JSON:

```json
{
  "beverageSegmentCode": "100",
  "beverageSegmentDescription": "WINE",
  "brandCode": "343",
  "gtin": "620654020010",
  "id": "1002",
  "itemCode": "100",
  "itemDescription": "INNA EST RIES VQA 750/12",
  "subBrandCode": "2391",
  "typeCode": "102",
  "universalSKUCode": "23011",
  "universalSKUDescription": "INNISKILLIN NIAGARA EST COL RIESLING 750ML",
  "upc": "062065402001",
  "varietalBlendCode": "632",
  "vintageDescription": "N/A"
}
```

Use a basic GET request to retrieve API data. For example, to find information for a specific item, you can query our Items API using the appropriate item ID. The ID for Inniskillin Riesling is 1002, so you can retrieve it as shown here.

<aside class="notice">
Be sure to replace YourAPIKey with the API key that you received after registering.
</aside>