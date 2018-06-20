{
  "info": {
    "name": "Icon Finder List all icons in an icon set",
    "_postman_id": "6daedc91-87b6-4e86-8020-f983d477a439",
    "description": "Provides a list of all icons in an icon set sorted descendingly by the popularity of the icons.List all icons in an icon set",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authors",
      "item": [
        {
          "id": "11e39f3a-8734-49c4-8398-940a9dbaf834",
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
              "id": "6c9bddaa-e7c4-4d31-84c8-e52310bc1b6f"
            }
          ]
        }
      ]
    },
    {
      "name": "Categories",
      "item": [
        {
          "id": "20b81e32-1c59-4c21-a752-e8fc475c7a6f",
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
              "id": "02f4eef1-3d32-429f-bce9-353d344d40bc"
            }
          ]
        },
        {
          "id": "3a6c1571-3bcc-4bd1-bcf9-fcc751ded02c",
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
              "id": "3a4e934c-88de-487a-8b31-4960eeacdf8d"
            }
          ]
        }
      ]
    },
    {
      "name": "Icons",
      "item": [
        {
          "id": "efdf5d85-2303-41fe-b4d5-5281841c4742",
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
              "id": "b90bb893-0f06-4014-9f63-ab0f961a056b"
            }
          ]
        },
        {
          "id": "9b5df749-7b19-40ae-9cc0-596775db861d",
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
              "id": "453e6179-5ea3-4ff7-a315-03bde359a7bd"
            }
          ]
        },
        {
          "id": "9f57161f-aa18-4cfb-91d4-55279d06b5b6",
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
              "id": "1d1b591f-bab6-4859-ba6f-c7e9c88fb89b"
            }
          ]
        }
      ]
    },
    {
      "name": "Licenses",
      "item": [
        {
          "id": "b9954b96-1c09-4ff2-aa23-6ddb2eb45d5d",
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
              "id": "952027e6-7078-46a4-a966-f2d841a47962"
            }
          ]
        }
      ]
    },
    {
      "name": "Styles",
      "item": [
        {
          "id": "a3ffaae2-1e92-40f7-a6d5-fa0cd1256b9a",
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
              "id": "96c947aa-4ae1-4726-8a68-fa06e079d25a"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "eabcad2e-0c01-405c-83a2-8ca2d1243cfe",
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
              "id": "10d893b8-0b8d-4319-bf7c-5813ba38ec61"
            }
          ]
        }
      ]
    }
  ]
}