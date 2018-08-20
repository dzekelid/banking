{
  "info": {
    "name": "Capital One DevExchange Get branch by id",
    "_postman_id": "9678d732-f096-4948-85f3-b3035fdb691b",
    "description": "Returns the branch with the specific id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "1156759c-e772-4f7d-9653-386ad989de9b",
          "name": "returns-the-branch-with-the-specific-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "branches/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the branch with the specific id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c98339d-1632-44ec-9a0d-1b0b7c504ed0"
            }
          ]
        }
      ]
    }
  ]
}