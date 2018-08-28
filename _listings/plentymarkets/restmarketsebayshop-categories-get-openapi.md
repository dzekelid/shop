---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List all eBay shop categories
  description: Lists all eBay shop categories.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---