{
  "info": {
    "name": "First Trust Bank (Open Banking) Get ATMs",
    "_postman_id": "e5570c36-ff3f-477a-a70a-a75c016c25c1",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "04bafe36-4dfd-416d-a6d1-44f691e89c73",
          "name": "getATMS",
          "request": {
            "url": "http://openapi.firsttrustbank.co.uk/open-banking/v2.1/atms/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4eed513-0957-4b6a-ae6d-cfd9926e7fe2"
            }
          ]
        }
      ]
    }
  ]
}