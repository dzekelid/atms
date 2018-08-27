{
  "info": {
    "name": "Royal Bank of Scotland Get ATMs",
    "_postman_id": "e4e68aa1-ef10-4bb1-8029-fe4250eb0e4b",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "bfe47a7c-1654-4403-b10b-aad2c49ccc71",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/atms/",
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
          "id": "bd0f55dc-45e7-4569-9a20-e30feec7c481"
        }
      ]
    }
  ]
}