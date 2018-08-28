swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
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
  /shops/{id}/storefronts:
    get:
      summary: Get Shops Storefronts
      description: Get storefront details on a shop.
      operationId: getShopsStorefronts
      x-api-path-slug: shopsidstorefronts-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Id
      - Storefronts
  /shops/{shop_id}/shipping_profiles:
    get:
      summary: Get Shops Shop Shipping Profiles
      description: List of shipping profiles for your shop
      operationId: getShopsShopShippingProfiles
      x-api-path-slug: shopsshop-idshipping-profiles-get
      parameters:
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Id
      - Shipping
      - Profiles
  /shops/{slug}:
    get:
      summary: Get Shops Slug
      description: Get details on a shop.
      operationId: getShopsSlug
      x-api-path-slug: shopsslug-get
      parameters:
      - in: query
        name: include_listing_count
        description: Include the live listing count in the response
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Slug
  /shops/{slug}/feedback:
    get:
      summary: Get Shops Slug Feedback
      description: Get shops slug feedback.
      operationId: getShopsSlugFeedback
      x-api-path-slug: shopsslugfeedback-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Slug
      - Feedback
  /shops/{slug}/feedback/buyer:
    get:
      summary: Get Shops Slug Feedback Buyer
      description: Get seller's feedback as a buyer
      operationId: getShopsSlugFeedbackBuyer
      x-api-path-slug: shopsslugfeedbackbuyer-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Slug
      - Feedback
      - Buyer
  /shops/{slug}/feedback/seller:
    get:
      summary: Get Shops Slug Feedback Seller
      description: Get seller's feedback as a seller
      operationId: getShopsSlugFeedbackSeller
      x-api-path-slug: shopsslugfeedbackseller-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Slug
      - Feedback
      - Seller