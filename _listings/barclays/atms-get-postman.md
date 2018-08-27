{
  "info": {
    "name": "Barclays Get ATMs",
    "_postman_id": "4f705bd5-8c45-4e21-acee-f47a4344acf7",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Atms",
      "item": [
        {
          "id": "26ebcccb-098d-46c3-87a7-13e32bd2641f",
          "name": "getATMS",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/atms/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba32382c-47f9-4b19-a46d-8320bf93dc17"
            }
          ]
        }
      ]
    }
  ]
}