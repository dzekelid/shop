---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Get Shop Vacation
  description: Returns shop vacation status
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /shop:
    get:
      summary: Get Shop
      description: Get your own shop details
      operationId: getShop
      x-api-path-slug: shop-get
      responses:
        200:
          description: OK
      tags:
      - Shop
    put:
      summary: Put Shop
      description: Update your shop profile
      operationId: putShop
      x-api-path-slug: shop-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Shop
  /shop/listing_conditions:
    get:
      summary: Get Shop Listing Conditions
      description: List of supported product conditions
      operationId: getShopListingConditions
      x-api-path-slug: shoplisting-conditions-get
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Listing
      - Conditions
  /shop/payment_methods:
    get:
      summary: Get Shop Payment Methods
      description: Get accepted payment methods
      operationId: getShopPaymentMethods
      x-api-path-slug: shoppayment-methods-get
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Payment
      - Methods
  /shop/vacation:
    delete:
      summary: Delete Shop Vacation
      description: Disable vacation mode. All listings will be re-enabled.
      operationId: deleteShopVacation
      x-api-path-slug: shopvacation-delete
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Vacation
    get:
      summary: Get Shop Vacation
      description: Returns shop vacation status
      operationId: getShopVacation
      x-api-path-slug: shopvacation-get
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Vacation
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