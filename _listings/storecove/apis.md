---
name: Storecove
x-slug: storecove
description: Storecove is Netherlands&rsquo; first online platform that provides people
  and companies with a way to view all their invoices in one online overview. Dolf
  Kars, founder and former owner of Videostrip (acquired by RTL Nederland), established
  Storecove in 2014 with cofounder Michael Riviera and Willem Stemfoort. Storecove
  mainly focuses on automatically collecting invoices, which saves time and money.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Shop
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/apis.md
specificationVersion: "0.14"
apis:
- name: Storecove - Get ShopAccountRequests
  x-api-slug: shop-account-requests-get
  description: |-
    Retrieve all active ShopAccountRequests for one of your entities.
    include::examples/shop_account_requests/shop_account_requests_index/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-account-requests-get-openapi.md
- name: Storecove - Create ShopAccountRequest
  x-api-slug: shop-account-requests-post
  description: |-
    Create a new ShopAccountRequest
    include::examples/shop_account_requests/create_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-account-requests-post-openapi.md
- name: Storecove - Delete ShopAccountRequest
  x-api-slug: shop-account-requestsid-delete
  description: |-
    Delete a specific ShopAccountRequest
    include::examples/shop_account_requests/delete_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-account-requestsid-delete-openapi.md
- name: Storecove - Get ShopAccountRequest
  x-api-slug: shop-account-requestsid-get
  description: |-
    Show a specific ShopAccountRequest
    include::examples/shop_account_requests/get_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-account-requestsid-get-openapi.md
- name: Storecove - Update ShopAccountRequest
  x-api-slug: shop-account-requestsid-patch
  description: |-
    Update a specific ShopAccountRequest
    include::examples/shop_account_requests/update_shop_account_request/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-account-requestsid-patch-openapi.md
- name: Storecove - Get ShopAccounts for an entity
  x-api-slug: shop-accounts-get
  description: |-
    Retrieve all active ShopAccounts for one of your entities.
    include::examples/shop_accounts/shop_accounts_index/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-accounts-get-openapi.md
- name: Storecove - Create ShopAccount
  x-api-slug: shop-accounts-post
  description: |-
    Create a new ShopAccount.
    include::examples/shop_accounts/create_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-accounts-post-openapi.md
- name: Storecove - Get ShopAccounts with authorization failures
  x-api-slug: shop-accountsauth-failures-get
  description: |-
    Get ShopAccounts with authorization failures.
    include::examples/shop_accounts/shop_accounts_auth_failures/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-accountsauth-failures-get-openapi.md
- name: Storecove - Delete ShopAccount
  x-api-slug: shop-accountsid-delete
  description: |-
    Delete a specific ShopAccount.
    include::examples/shop_accounts/delete_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-accountsid-delete-openapi.md
- name: Storecove - Get ShopAccount
  x-api-slug: shop-accountsid-get
  description: |-
    Get a specific ShopAccount.
    include::examples/shop_accounts/get_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-accountsid-get-openapi.md
- name: Storecove - Update ShopAccount
  x-api-slug: shop-accountsid-patch
  description: |-
    Update a specific ShopAccount.
    include::examples/shop_accounts/update_shop_account/tabs.adoc[]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/storecove-logo.jpg
  humanURL: http://www.storecove.com
  baseURL: https://api.storecove.com//api/v2
  tags: Invoices, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shop/master/_listings/storecove/shop-accountsid-patch-openapi.md
x-common:
- type: x-website
  url: http://www.storecove.com
- type: x-api-gallery
  url: http://stocktwits.api.gallery.streamdata.io
- type: x-api-stack
  url: http://storecove.stack.network
- type: x-blog
  url: https://www.storecove.com/blog/
- type: x-blog-rss
  url: https://www.storecove.com/blog/rss/
- type: x-documentation
  url: https://www.storecove.com/en/docs
- type: x-github
  url: https://github.com/storecove
- type: x-openapi
  url: https://www.storecove.com/api/v2/openapi.json
- type: x-twitter
  url: https://twitter.com/storecove
- type: x-website
  url: http://storecove.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---