---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/products/9579007950.json:
    delete:
      summary: Remove a product from the shop
      description: Remove a product from the shop.
      operationId: deleteAdminProducts9579007950.json
      x-api-path-slug: adminproducts9579007950-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Remove
      - Product
      - From
      - Shop
  /admin/pages/count.json:
    get:
      summary: Count all pages for a shop
      description: Count all pages for a shop.
      operationId: getAdminPagesCount.json
      x-api-path-slug: adminpagescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Pagesa
      - Shop
  /admin/webhooks.json:
    get:
      summary: Get a list of all webhooks for your shop.
      description: Get a list of all webhooks for your shop..
      operationId: getAdminWebhooks.json
      x-api-path-slug: adminwebhooks-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Webhooksyour
      - Shop
  /admin/webhooks/count.json:
    get:
      summary: Get a count of all webhooks for your shop.
      description: Get a count of all webhooks for your shop..
      operationId: getAdminWebhooksCount.json
      x-api-path-slug: adminwebhookscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Webhooksyour
      - Shop
  /admin/themes/110163843/assets.json:
    delete:
      summary: Remove assets from your shop
      description: Remove assets from your shop.
      operationId: deleteAdminThemes110163843Assets.json
      x-api-path-slug: adminthemes110163843assets-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Remove
      - Assets
      - From
      - Your
      - Shop
  /admin/locations.json:
    get:
      summary: Get a list of all locations for a shop
      description: Get a list of all locations for a shop.
      operationId: getAdminLocations.json
      x-api-path-slug: adminlocations-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Locationsa
      - Shop
  /admin/customer_saved_searches.json:
    get:
      summary: Get all customer saved searches for a shop
      description: Get all customer saved searches for a shop.
      operationId: getAdminCustomerSavedSearches.json
      x-api-path-slug: admincustomer-saved-searches-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Customer
      - Saved
      - Searchesa
      - Shop
  /admin/shop.json:
    get:
      summary: Get the configuration of the shop account
      description: Get the configuration of the shop account.
      operationId: getAdminShop.json
      x-api-path-slug: adminshop-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Configuration
      - Shop
      - Account
  /admin/themes.json:
    get:
      summary: Get all shop themes
      description: Get all shop themes.
      operationId: getAdminThemes.json
      x-api-path-slug: adminthemes-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Shop
      - Themes
---