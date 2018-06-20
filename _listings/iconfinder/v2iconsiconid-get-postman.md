{
  "info": {
    "name": "Icon Finder Get icon details",
    "_postman_id": "753c9c4c-428c-4f78-b4d3-038633cd2005",
    "description": "Get details about a specific ico",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authors",
      "item": [
        {
          "id": "2168d114-cbd3-405d-a043-db824c21861d",
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
              "id": "d8f8e896-2abe-428f-b81d-3d3d5553e4cd"
            }
          ]
        }
      ]
    },
    {
      "name": "Categories",
      "item": [
        {
          "id": "8b4dd158-d030-490c-9775-4a5b79f8ad1c",
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
              "id": "e170c703-34b7-49f2-a699-ce136a81a459"
            }
          ]
        },
        {
          "id": "aabcb969-62f3-4741-9d7e-b623b1a3a8e2",
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
              "id": "e2c98ea8-6381-4a8c-8045-565ea7bc8ba8"
            }
          ]
        }
      ]
    },
    {
      "name": "Icons",
      "item": [
        {
          "id": "0d1c8f67-a8cf-4b9d-932e-2106b4906080",
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
              "id": "ff884c0b-a6d7-4ed3-b380-b07750ec240b"
            }
          ]
        },
        {
          "id": "8e50501d-e74e-4c82-8b69-9d59ddfa37f3",
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
              "id": "8be07773-cda6-4e40-bfe3-434ad1e978f5"
            }
          ]
        }
      ]
    },
    {
      "name": "Licenses",
      "item": [
        {
          "id": "b9bc83ec-e734-47ee-bb0e-99b3e2b27147",
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
              "id": "b948e9f0-1878-43a5-b47c-8d5579afac46"
            }
          ]
        }
      ]
    },
    {
      "name": "Styles",
      "item": [
        {
          "id": "8711a140-1bbc-4c34-802c-009c8fc17eb4",
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
              "id": "04f5f6e1-a492-41c7-9f03-ff476293de3d"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "9b8114a1-a71c-496c-a719-24238d86914b",
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
              "id": "a25b068a-60af-4f21-869a-4dd5fc87636a"
            }
          ]
        }
      ]
    }
  ]
}