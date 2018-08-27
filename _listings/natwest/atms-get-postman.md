{
  "info": {
    "name": "NatWest Get ATMs",
    "_postman_id": "a26b80ec-fc5e-497d-9207-9b0073d918de",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "a493d198-34fc-44f1-bed4-a1378d2d0bf5",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/atms/",
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
          "id": "866994e9-5041-4f11-85a1-bab962eec6ee"
        }
      ]
    }
  ]
}