{
  "info": {
    "name": "Hacker News Returns the current top 100 stories.",
    "_postman_id": "e08dedb2-bf7d-4cf1-9db6-19224c801b73",
    "description": "Returns the current top 100 stories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Links",
      "item": [
        {
          "id": "34c2bb9a-dd35-4079-9673-73183cf1730c",
          "name": "get",
          "request": {
            "url": "http://hacker-news.firebaseio.com/v0/updates.json",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the changed items and profiles"
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "a562564f-cef9-4d57-bbd0-1041dca637ce"
            }
          ]
        },
        {
          "id": "7ab00251-abca-40db-8867-8055e809a0fc",
          "name": "get_top_stories",
          "request": {
            "url": "http://hacker-news.firebaseio.com/v0/topstories.json",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the current top 100 stories."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "8bf3ba93-3aa2-413a-9f8d-f3112387cc37"
            }
          ]
        }
      ]
    }
  ]
}