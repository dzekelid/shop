---
swagger: "2.0"
x-collection-name: Storecove
x-complete: 0
info:
  title: Storecove Get ShopAccounts with authorization failures
  description: |-
    Get ShopAccounts with authorization failures.
    include::examples/shop_accounts/shop_accounts_auth_failures/tabs.adoc[]
  version: 2.0.1
host: api.storecove.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /shop_account_requests:
    get:
      summary: Get ShopAccountRequests
      description: |-
        Retrieve all active ShopAccountRequests for one of your entities.
        include::examples/shop_account_requests/shop_account_requests_index/tabs.adoc[]
      operationId: shop_account_requests_index
      x-api-path-slug: shop-account-requests-get
      parameters:
      - in: query
        name: external_user_id
        description: Filter by the external_user_id
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
    post:
      summary: Create ShopAccountRequest
      description: |-
        Create a new ShopAccountRequest
        include::examples/shop_account_requests/create_shop_account_request/tabs.adoc[]
      operationId: create_shop_account_request
      x-api-path-slug: shop-account-requests-post
      parameters:
      - in: body
        name: shop_account_request
        description: ShopAccountRequest to add
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
  /shop_account_requests/{id}:
    delete:
      summary: Delete ShopAccountRequest
      description: |-
        Delete a specific ShopAccountRequest
        include::examples/shop_account_requests/delete_shop_account_request/tabs.adoc[]
      operationId: delete_shop_account_request
      x-api-path-slug: shop-account-requestsid-delete
      parameters:
      - in: path
        name: id
        description: shop_account_request id
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
    get:
      summary: Get ShopAccountRequest
      description: |-
        Show a specific ShopAccountRequest
        include::examples/shop_account_requests/get_shop_account_request/tabs.adoc[]
      operationId: get_shop_account_request
      x-api-path-slug: shop-account-requestsid-get
      parameters:
      - in: path
        name: id
        description: shop_account_request id
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
    patch:
      summary: Update ShopAccountRequest
      description: |-
        Update a specific ShopAccountRequest
        include::examples/shop_account_requests/update_shop_account_request/tabs.adoc[]
      operationId: update_shop_account_request
      x-api-path-slug: shop-account-requestsid-patch
      parameters:
      - in: path
        name: id
        description: shop_account_request id
      - in: body
        name: shop_account_request
        description: ShopAccountRequest updates
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Account
      - Requests
  /shop_accounts:
    get:
      summary: Get ShopAccounts for an entity
      description: |-
        Retrieve all active ShopAccounts for one of your entities.
        include::examples/shop_accounts/shop_accounts_index/tabs.adoc[]
      operationId: shop_accounts_index
      x-api-path-slug: shop-accounts-get
      parameters:
      - in: query
        name: external_user_id
        description: Filter by the external_user_id
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Accounts
    post:
      summary: Create ShopAccount
      description: |-
        Create a new ShopAccount.
        include::examples/shop_accounts/create_shop_account/tabs.adoc[]
      operationId: create_shop_account
      x-api-path-slug: shop-accounts-post
      parameters:
      - in: body
        name: shop_account
        description: ShopAccount to add
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Accounts
  /shop_accounts/auth_failures:
    get:
      summary: Get ShopAccounts with authorization failures
      description: |-
        Get ShopAccounts with authorization failures.
        include::examples/shop_accounts/shop_accounts_auth_failures/tabs.adoc[]
      operationId: shop_accounts_auth_failures
      x-api-path-slug: shop-accountsauth-failures-get
      responses:
        200:
          description: OK
      tags:
      - Shop
      - Accounts
      - Auth
      - Failures
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