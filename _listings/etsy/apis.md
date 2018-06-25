---
name: Etsy
x-slug: etsy
description: Find handmade, vintage, and unique goods that express who you are.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
x-kinRank: "9"
x-alexaRank: "187"
tags: Shops
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/apis.md
specificationVersion: "0.14"
apis:
- name: Etsy Get Shops Shop Listings Active
  x-api-slug: etsy
  description: Finds all active Listings associated with a Shop
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/active
  tags: Shops,Shop,Listings,Active
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsactive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsactive-get-openapi.md
- name: Etsy Get Shops Shop
  x-api-slug: etsy
  description: Retrieves a Shop by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}
  tags: Shops,Shop
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-id-get-openapi.md
- name: Etsy Put Shops Shop
  x-api-slug: etsy
  description: Updates a Shop
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}
  tags: Shops,Shop
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-id-put-openapi.md
- name: Etsy Get Shops Shop Receipts
  x-api-slug: etsy
  description: Retrieves a set of Receipt objects associated to a Shop.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/receipts
  tags: Shops,Shop,Receipts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idreceipts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idreceipts-get-openapi.md
- name: Etsy Get Shops Shop Transactions
  x-api-slug: etsy
  description: Retrieves a set of Transaction objects associated to a Shop.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/transactions
  tags: Shops,Shop,Transactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idtransactions-get-openapi.md
- name: Etsy Get Shops Shop Sections
  x-api-slug: etsy
  description: Retrieves a set of ShopSection objects associated to a Shop.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/sections
  tags: Shops,Shop,Sections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idsections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idsections-get-openapi.md
- name: Etsy Get Shops
  x-api-slug: etsy
  description: Finds all Shops. If there is a keywords parameter, finds shops with
    shop_name starting with keywords.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops
  tags: Shops
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shops-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shops-get-openapi.md
- name: Etsy Get Shops Shop Listings Featured
  x-api-slug: etsy
  description: Retrieves Listings associated to a Shop that are featured
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/featured
  tags: Shops,Shop,Listings,Featured
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsfeatured-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsfeatured-get-openapi.md
- name: Etsy Get Shops Shop Listings Inactive
  x-api-slug: etsy
  description: Retrieves Listings associated to a Shop that are inactive
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/inactive
  tags: Shops,Shop,Listings,Inactive
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsinactive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsinactive-get-openapi.md
- name: Etsy Get Shops Shop Listings Expired
  x-api-slug: etsy
  description: Retrieves Listings associated to a Shop that are expired
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/expired
  tags: Shops,Shop,Listings,Expired
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsexpired-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsexpired-get-openapi.md
- name: Etsy Get Shops Shop Listings Inactive Listing
  x-api-slug: etsy
  description: Retrieves a Listing associated to a Shop that is inactive
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/inactive/{listing_id}
  tags: Shops,Shop,Listings,Inactive,Listing
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsinactivelisting-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsinactivelisting-id-get-openapi.md
- name: Etsy Get Shops Shop Listings Expired Listing
  x-api-slug: etsy
  description: Retrieves a Listing associated to a Shop that is inactive
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/expired/{listing_id}
  tags: Shops,Shop,Listings,Expired,Listing
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsexpiredlisting-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idlistingsexpiredlisting-id-get-openapi.md
- name: Etsy Post Shops Shop Appearance Banner
  x-api-slug: etsy
  description: Upload a new shop banner image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/appearance/banner
  tags: Shops,Shop,Appearance,Banner
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idappearancebanner-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idappearancebanner-post-openapi.md
- name: Etsy Delete Shops Shop Appearance Banner Shop Banner
  x-api-slug: etsy
  description: Deletes a shop banner image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/appearance/banner/{shop_banner_id}
  tags: Shops,Shop,Appearance,Banner,Shop,Banner
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idappearancebannershop-banner-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/shopsshop-idappearancebannershop-banner-id-delete-openapi.md
- name: Etsy Get Users User Shops
  x-api-slug: etsy
  description: Retrieves a set of Shop objects associated to a User.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///users/{user_id}/shops
  tags: Users,Shops
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/usersuser-idshops-get-openapi.md
- name: Etsy
  x-api-slug: etsy
  description: Etsy is a handmade marketplace. The Etsy API lets developers tap into
    the Etsy community, building their own Etsy-powered applications for the web,
    desktop and mobile devices. Applications built on the API will connect buyers
    with sellers, promote the handmade lifestyle, and support the craftspeople who
    sell on Etsy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private/
  tags: Shops
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/shops/master/_listings/etsy/openapi.md
x-common:
- type: x-api-json--authoritative
  url: http://apis.io/apisdef/etsy.json
- type: x-application-gallery
  url: https://www.etsy.com/apps/
- type: x-base
  url: https://openapi.etsy.com/
- type: x-blog
  url: http://www.etsy.com/blog/en/
- type: x-blog-rss
  url: https://blog.etsy.com/en/feed/
- type: x-copyright
  url: https://www.etsy.com/help/article/482/?ref=ftr
- type: x-crunchbase
  url: https://crunchbase.com/organization/etsy
- type: x-crunchbase
  url: http://www.crunchbase.com/company/etsy
- type: x-developer
  url: https://www.etsy.com/developers/
- type: x-email
  url: enaffiliates@etsy.com
- type: x-email
  url: selleraffiliate@etsy.com
- type: x-email
  url: developer@etsy.com
- type: x-email
  url: legal@etsy.com
- type: x-email
  url: dpo@etsy.com
- type: x-email
  url: dispute-resolution@etsy.com
- type: x-forum
  url: https://www.etsy.com/developers/discussion
- type: x-github
  url: https://github.com/etsy
- type: x-privacy
  url: https://www.etsy.com/help/article/480/?ref=ftr
- type: x-terms-of-service
  url: https://www.etsy.com/help/article/479/?ref=ftr
- type: x-transparency-report
  url: http://blog.etsy.com/news/files/2015/07/Etsy_TransparencyReport_2014.pdf
- type: x-twitter
  url: https://twitter.com/Etsy
- type: x-website
  url: http://www.etsy.com/
- type: x-website
  url: http://etsy.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---