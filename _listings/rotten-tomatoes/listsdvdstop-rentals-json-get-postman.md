{
  "info": {
    "name": "Rotten Tomatoes Get Lists Dvds Top Rentals",
    "_postman_id": "89fd2b16-2575-4157-9a98-f7e75780e3e3",
    "description": "Get lists dvds top rentals.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "2b553710-fa75-448a-867c-5d64df436452",
          "name": "getLists.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bf07f26-09a4-4589-ab0c-4792706c7238"
            }
          ]
        },
        {
          "id": "1783b2e2-37b7-4a9c-81ad-c5e92a077163",
          "name": "getListsDvds.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcd5b905-2a58-4153-83df-9be6690cb522"
            }
          ]
        },
        {
          "id": "4a375e02-44bb-4b5c-95d7-52339a78edc2",
          "name": "getListsDvdsCurrentReleases.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/current_releases.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds current releases.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fc6a47d-5eac-42bb-9765-2a99f8fd4729"
            }
          ]
        },
        {
          "id": "b9c48bae-5aa6-4146-9743-493b5e2795e0",
          "name": "getListsDvdsNewReleases.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/new_releases.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds new releases.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ce4d6c4-2a9c-431d-83d0-f676601127de"
            }
          ]
        },
        {
          "id": "2cf9755f-d629-4fe9-859a-67f8d23c2120",
          "name": "getListsDvdsTopRentals.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/top_rentals.json?country=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds top rentals.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd563c1d-c66e-4886-af47-752ddc586360"
            }
          ]
        }
      ]
    }
  ]
}