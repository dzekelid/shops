---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Post My Follows Shops Slug
  description: Post my follows shops slug.
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
  /my/follows/shops/{slug}:
    delete:
      summary: Delete My Follows Shops Slug
      description: Delete my follows shops slug.
      operationId: deleteMyFollowsShopsSlug
      x-api-path-slug: myfollowsshopsslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Shops
      - Slug
    get:
      summary: Get My Follows Shops Slug
      description: Get my follows shops slug.
      operationId: getMyFollowsShopsSlug
      x-api-path-slug: myfollowsshopsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Shops
      - Slug
    post:
      summary: Post My Follows Shops Slug
      description: Post my follows shops slug.
      operationId: postMyFollowsShopsSlug
      x-api-path-slug: myfollowsshopsslug-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Shops
      - Slug
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