{
  "info": {
    "name": "Bank of Scotland Get ATMs",
    "_postman_id": "be9b2770-c75d-4e85-97b1-10a4fccee6e0",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "1f0e495c-c834-4eb3-bbf3-3e5602e700d4",
          "name": "getATMS",
          "request": {
            "url": "http://api.bankofscotland.co.uk/open-banking/v2.1/atms/",
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
              "id": "6203e370-033a-48df-ac66-59f7a7a69243"
            }
          ]
        }
      ]
    }
  ]
}