{
  "info": {
    "name": "Halifax Bank Get ATMs",
    "_postman_id": "244f4552-f9f2-49fc-a75b-2584f5d6f528",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "46a5bf13-7b5a-4755-854b-9f0b8dfc601d",
          "name": "getATMS",
          "request": {
            "url": "http://api.halifax.co.uk/open-banking/v2.1/atms/",
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
              "id": "3541859a-221b-4a23-accd-019af035e0f5"
            }
          ]
        }
      ]
    }
  ]
}