{
  "info": {
    "name": "Danske Bank Get ATMs",
    "_postman_id": "66429fad-b216-4c95-bf0b-1d41801a9496",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "2f8d12c8-787f-4b38-be2d-75052d5a0fb4",
      "name": "getATMS",
      "request": {
        "url": "http://obp-data.danskebank.com/open-banking/v2.1/atms/",
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
          "id": "f50fa6ef-94f2-4a2b-88fc-2397b638f994"
        }
      ]
    }
  ]
}