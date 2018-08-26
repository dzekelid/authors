{
  "info": {
    "name": "Icon Finder Get author details",
    "_postman_id": "012977ea-1041-40f5-9f11-b56f5fdf7d0b",
    "description": "Get details about a specific author identified by a unique ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authors",
      "item": [
        {
          "id": "e64c9a95-62dd-4c05-8159-2e84053d6224",
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
              "id": "2e633c36-abec-43eb-9c40-d35a65ceb188"
            }
          ]
        }
      ]
    }
  ]
}