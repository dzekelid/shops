---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify getting the shops policies
  description: Getting the shops policies.
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
  /admin/policies.json:
    get:
      summary: getting the shops policies
      description: Getting the shops policies.
      operationId: getAdminPolicies.json
      x-api-path-slug: adminpolicies-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Getting
      - Shops
      - Policies
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