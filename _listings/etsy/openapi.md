swagger: "2.0"
x-collection-name: Etsy
x-complete: 1
info:
  title: Etsy
  description: bring-etsys-handmade-marketplace-and-community-into-your-apps-
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
  /shops:
    get:
      summary: Get Shops
      description: Finds all Shops. If there is a keywords parameter, finds shops
        with shop_name starting with keywords.
      operationId: getShops
      x-api-path-slug: shops-get
      parameters:
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: shop_name
        description: Bring Etsys handmade marketplace and community into your apps
      responses:
        200:
          description: OK
      tags:
      - Shops
  /shops/{shop_id}/listings/featured:
    get:
      summary: Get Shops Shop Listings Featured
      description: Retrieves Listings associated to a Shop that are featured
      operationId: getShopsShopListingsFeatured
      x-api-path-slug: shopsshop-idlistingsfeatured-get
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
      - Listings
      - Featured
  /shops/{shop_id}/listings/inactive:
    get:
      summary: Get Shops Shop Listings Inactive
      description: Retrieves Listings associated to a Shop that are inactive
      operationId: getShopsShopListingsInactive
      x-api-path-slug: shopsshop-idlistingsinactive-get
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
      - Listings
      - Inactive
  /shops/{shop_id}/listings/expired:
    get:
      summary: Get Shops Shop Listings Expired
      description: Retrieves Listings associated to a Shop that are expired
      operationId: getShopsShopListingsExpired
      x-api-path-slug: shopsshop-idlistingsexpired-get
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
      - Listings
      - Expired
  /shops/{shop_id}/listings/inactive/{listing_id}:
    get:
      summary: Get Shops Shop Listings Inactive Listing
      description: Retrieves a Listing associated to a Shop that is inactive
      operationId: getShopsShopListingsInactiveListing
      x-api-path-slug: shopsshop-idlistingsinactivelisting-id-get
      parameters:
      - in: path
        name: listing_id
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Listings
      - Inactive
      - Listing
  /shops/{shop_id}/listings/expired/{listing_id}:
    get:
      summary: Get Shops Shop Listings Expired Listing
      description: Retrieves a Listing associated to a Shop that is inactive
      operationId: getShopsShopListingsExpiredListing
      x-api-path-slug: shopsshop-idlistingsexpiredlisting-id-get
      parameters:
      - in: path
        name: listing_id
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Listings
      - Expired
      - Listing
  /shops/{shop_id}/appearance/banner:
    post:
      summary: Post Shops Shop Appearance Banner
      description: Upload a new shop banner image
      operationId: postShopsShopAppearanceBanner
      x-api-path-slug: shopsshop-idappearancebanner-post
      parameters:
      - in: query
        name: image
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Appearance
      - Banner
  /shops/{shop_id}/appearance/banner/{shop_banner_id}:
    delete:
      summary: Delete Shops Shop Appearance Banner Shop Banner
      description: Deletes a shop banner image
      operationId: deleteShopsShopAppearanceBannerShopBanner
      x-api-path-slug: shopsshop-idappearancebannershop-banner-id-delete
      parameters:
      - in: path
        name: shop_banner_id
      - in: path
        name: shop_id
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Appearance
      - Banner
      - Shop
      - Banner
  /users/{user_id}/shops:
    get:
      summary: Get Users User Shops
      description: Retrieves a set of Shop objects associated to a User.
      operationId: getUsersUserShops
      x-api-path-slug: usersuser-idshops-get
      parameters:
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Shops