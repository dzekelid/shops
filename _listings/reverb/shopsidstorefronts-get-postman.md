{
  "info": {
    "name": "reverb Get Shops Storefronts",
    "_postman_id": "442fc356-0b73-4637-a65f-1fd73ec3ffb5",
    "description": "Get storefront details on a shop.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "c807f88c-aa85-4dc6-9895-555cda5fef55",
          "name": "getMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "026824f6-8336-45f2-9ffc-ea43e161378c"
            }
          ]
        },
        {
          "id": "0f37af31-5f31-432e-be7f-8026f49a7e75",
          "name": "postMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "731b1ecc-4de8-42d3-823b-693a99156d20"
            }
          ]
        },
        {
          "id": "7617dcfa-2bfa-491e-9ee5-7f0eb8d83622",
          "name": "deleteMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ccf3f32-5577-4184-8ca3-42a930942752"
            }
          ]
        }
      ]
    },
    {
      "name": "Shops",
      "item": [
        {
          "id": "5bdf6048-0556-44e3-be42-fa0c6ade737a",
          "name": "getShopsStorefronts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "shops/:id/storefronts"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get storefront details on a shop."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42ccdf0d-7c2b-41fa-81f6-ad63e0ee661b"
            }
          ]
        }
      ]
    }
  ]
}