{
  "info": {
    "name": "HSBC Get ATMs",
    "_postman_id": "6f0b82f3-aa0e-424f-8ec2-60bd6c42d76e",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "4216a592-0a91-4aed-aff3-9d20618ff04f",
          "name": "getATMS",
          "request": {
            "url": "http://api.hsbc.com/open-banking/v2.1/atms/",
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
              "id": "b48af4da-bed8-4221-adda-aa61968d22b3"
            }
          ]
        }
      ]
    }
  ]
}