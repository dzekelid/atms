{
  "info": {
    "name": "Bank of Ireland Get Atms",
    "_postman_id": "7811c67c-f6c5-4d12-929b-f34fddf12b54",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "0ac496bb-8817-4739-af11-525939892fc3",
          "name": "getATMS",
          "request": {
            "url": "http://openapi.bankofireland.com/open-banking/v2.1/atms/",
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
              "id": "878893e3-07a9-402a-8c4e-a5f5a59f77bd"
            }
          ]
        }
      ]
    }
  ]
}