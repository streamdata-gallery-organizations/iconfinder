{
  "info": {
    "name": "Icon Finder List all styles",
    "_postman_id": "cfae85a0-f3f3-4581-88b3-849a403dc770",
    "description": "List all styles sorted ascendingly by their identifier.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authors",
      "item": [
        {
          "id": "424f6f84-1b68-4085-9c36-1aa06654f766",
          "name": "getAuthorsAuthor",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.iconfinder.com",
              "path": [
                "v2",
                "authors/:authorID"
              ],
              "query": [
                {
                  "key": "authors",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "authorID",
                  "value": "authorID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get details about a specific author identified by a unique ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f33dd26-5ba5-40b8-8316-4b48ef6edfd3"
            }
          ]
        }
      ]
    },
    {
      "name": "Categories",
      "item": [
        {
          "id": "f3f0cc4c-6083-473d-9c4d-7a2348b02ef4",
          "name": "getCategories",
          "request": {
            "url": "http://api.iconfinder.com/v2/categories?after=%7B%7D&count=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all categories sorted ascendingly by their identifier."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c0891dc-8946-4e25-a0ca-6f1023b14959"
            }
          ]
        },
        {
          "id": "f97fa3bf-bd92-495e-b519-e170da54f875",
          "name": "getV2CategoriesCategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.iconfinder.com",
              "path": [
                "v2",
                "v2/categories/:categoryID"
              ],
              "variable": [
                {
                  "id": "categoryID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get details about a specific category identified by its identifier."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81695981-603f-436e-87b2-153e28dbb9f9"
            }
          ]
        }
      ]
    },
    {
      "name": "Icons",
      "item": [
        {
          "id": "ddbdc7ec-09f9-45aa-8376-3b10595d0a86",
          "name": "getIconsSearch",
          "request": {
            "url": "http://api.iconfinder.com/v2/icons/search?category=%7B%7D&count=%7B%7D&license=%7B%7D&maximum_size=%7B%7D&minimum_size=%7B%7D&offset=%7B%7D&premium=%7B%7D&query=%7B%7D&style=%7B%7D&vector=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search through icons by various criteria. The returned list of icons is ordered descendingly by popularit"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d988eba-ba18-455a-94ab-1b9da8b055f1"
            }
          ]
        },
        {
          "id": "e0d93a4b-8711-4fb1-95b6-1040a6b32c7c",
          "name": "getV2IconsIcon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.iconfinder.com",
              "path": [
                "v2",
                "v2/icons/:iconID"
              ],
              "variable": [
                {
                  "id": "iconID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get details about a specific ico"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef5fe0ea-6df9-404b-83bd-07fcc6b06dbd"
            }
          ]
        },
        {
          "id": "cc68eb67-bb76-4e38-a8b0-843055a8282a",
          "name": "getV2IconsetsIconIcons",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.iconfinder.com",
              "path": [
                "v2",
                "v2/iconsets/:iconID/icons"
              ],
              "query": [
                {
                  "key": "after",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "List all icons in an icon set",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "iconID",
                  "value": "iconID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides a list of all icons in an icon set sorted descendingly by the popularity of the icons.List all icons in an icon set"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7a4f195-2ac2-45c3-ad8a-7cce51ac7fb4"
            }
          ]
        }
      ]
    },
    {
      "name": "Licenses",
      "item": [
        {
          "id": "381aced0-f473-4eba-9e95-f92bf79c1022",
          "name": "getLicensesLicense",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.iconfinder.com",
              "path": [
                "v2",
                "licenses/:licenseID"
              ],
              "variable": [
                {
                  "id": "licenseID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get details about a specific license by its unique ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49c03301-88e5-414d-8cd9-2f8bb4b3843d"
            }
          ]
        }
      ]
    },
    {
      "name": "Styles",
      "item": [
        {
          "id": "f1667e9f-9533-4516-8d62-c61c171d1566",
          "name": "getStylesStyle",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.iconfinder.com",
              "path": [
                "v2",
                "styles/:styleID"
              ],
              "variable": [
                {
                  "id": "styleID",
                  "value": "styleID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get details about a specific style identified by its identifier."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f43fca0c-795e-4357-a5a3-bb6ed8985dbc"
            }
          ]
        },
        {
          "id": "81be9c9a-3250-4c99-b03d-fbc8e39196c1",
          "name": "getV2Styles",
          "request": {
            "url": "http://api.iconfinder.com/v2/v2/styles?after=%7B%7D&count=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all styles sorted ascendingly by their identifier."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e4a9665-4a9b-488e-8706-3be26b5480b3"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "f55d5a84-11e7-4ae3-9946-85dd151840c8",
          "name": "getUser",
          "request": {
            "url": "http://api.iconfinder.com/v2/user",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets an authenticated user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc789437-b157-4ffb-bf07-8d85dc682574"
            }
          ]
        }
      ]
    }
  ]
}