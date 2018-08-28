swagger: "2.0"
x-collection-name: Storecove
x-complete: 1
info:
  title: Storecove
  description: storecove-api
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
  /shops:
    get:
      summary: Get Shops
      description: |-
        Get all available shops.
        include::examples/shops/shops_index/tabs.adoc[]
      operationId: shops_index
      x-api-path-slug: shops-get
      responses:
        200:
          description: OK
      tags:
      - Shops