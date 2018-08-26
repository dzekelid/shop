---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 0
info:
  title: Etsy Get Shops Shop Sections
  description: Retrieves a set of ShopSection objects associated to a Shop.
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /shops/{shop_id}/listings/active:
    get:
      summary: Get Shops Shop Listings Active
      description: Finds all active Listings associated with a Shop
      operationId: getShopsShopListingsActive
      x-api-path-slug: shopsshop-idlistingsactive-get
      parameters:
      - in: query
        name: category
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: color
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: color_accuracy
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: keywords
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: materials
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: max_price
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: min_price
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: path
        name: shop_id
      - in: query
        name: sort_on
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: sort_order
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: tags
        description: Bring Etsys handmade marketplace and community into your apps
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Listings
      - Active
  /shops/{shop_id}:
    get:
      summary: Get Shops Shop
      description: Retrieves a Shop by id.
      operationId: getShopsShop
      x-api-path-slug: shopsshop-id-get
      parameters:
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
    put:
      summary: Put Shops Shop
      description: Updates a Shop
      operationId: putShopsShop
      x-api-path-slug: shopsshop-id-put
      parameters:
      - in: query
        name: alchemy_message
      - in: query
        name: announcement
      - in: query
        name: is_refusing_alchemy
      - in: query
        name: policy_additional
      - in: query
        name: policy_payment
      - in: query
        name: policy_refunds
      - in: query
        name: policy_shipping
      - in: query
        name: policy_welcome
      - in: query
        name: sale_message
      - in: path
        name: shop_id
      - in: query
        name: title
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
  /shops/{shop_id}/receipts:
    get:
      summary: Get Shops Shop Receipts
      description: Retrieves a set of Receipt objects associated to a Shop.
      operationId: getShopsShopReceipts
      x-api-path-slug: shopsshop-idreceipts-get
      parameters:
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Receipts
  /shops/{shop_id}/transactions:
    get:
      summary: Get Shops Shop Transactions
      description: Retrieves a set of Transaction objects associated to a Shop.
      operationId: getShopsShopTransactions
      x-api-path-slug: shopsshop-idtransactions-get
      parameters:
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Transactions
  /shops/{shop_id}/sections:
    get:
      summary: Get Shops Shop Sections
      description: Retrieves a set of ShopSection objects associated to a Shop.
      operationId: getShopsShopSections
      x-api-path-slug: shopsshop-idsections-get
      parameters:
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Sections
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