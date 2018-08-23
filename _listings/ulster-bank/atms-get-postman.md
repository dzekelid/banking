{
  "info": {
    "name": "Ulster Bank Get ATMs",
    "_postman_id": "a553be7d-d429-4da4-be81-79f3c765b1ec",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "c9bd4b7e-04c4-47cc-81b2-befe2543651f",
          "name": "getATMS",
          "request": {
            "url": "http://openapi.ulsterbank.co.uk/open-banking/v2.1/atms/",
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
              "id": "a3fa4cd6-3447-4198-9529-8ed8e963b881"
            }
          ]
        }
      ]
    }
  ]
}