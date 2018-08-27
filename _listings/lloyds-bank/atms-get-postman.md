{
  "info": {
    "name": "Lloyds Bank Get ATMs",
    "_postman_id": "97adb463-e04f-49c1-a60e-c3b4cbde614b",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Atms",
      "item": [
        {
          "id": "6d545c65-cf8b-45a4-b707-726153918535",
          "name": "getATMS",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/atms/",
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
              "id": "2f0551ff-4e6f-4e9e-8f58-a74117f20795"
            }
          ]
        }
      ]
    }
  ]
}