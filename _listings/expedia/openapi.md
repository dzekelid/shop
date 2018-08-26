---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 1
info:
  title: Expedia
  description: expedia-mobile-api-documentation--brfont-colorblue-note-in-case-of-authorization-exception-just-a-hrefstaticmobileswaggeruiusersigninusersigninafont
  version: 0.0.1
host: apim.expedia.com
basePath: x/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /lx/api/search:
    get:
      summary: Search
      description: LX Shop Search
      operationId: lx-search
      x-api-path-slug: lxapisearch-get
      parameters:
      - in: query
        name: endDate
        description: (optional) dates in YYY-MM-DD format (preferred) or POS configuration
          format (e
      - in: query
        name: langid
        description: Use langid as defined for a POS secondary language
      - in: query
        name: location
        description: This represents the location in POS configuration language, the
          term is more accurate if it is closer to ESS representation of region
      - in: query
        name: startDate
        description: (optional) dates in YYY-MM-DD format (preferred) or POS configuration
          format (e
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Shop
---