---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/markets/ebay/shop_categories:
    get:
      summary: List all eBay shop categories
      description: Lists all eBay shop categories.
      operationId: getRestMarketsEbayShopCategories
      x-api-path-slug: restmarketsebayshop-categories-get
      parameters:
      - in: query
        name: credentialsId
        description: The credentials ID for whom to fetch eBay shop categories
      - in: query
        name: viewType
        description: How should the eBay shop categories be returned
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - EBay
      - Shop
      - Categories
---