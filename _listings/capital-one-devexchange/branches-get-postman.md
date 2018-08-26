{
  "info": {
    "name": "Capital One DevExchange Get all branches",
    "_postman_id": "45d92681-f91e-44de-b496-6ce659c5dba9",
    "description": "Returns all of the Capital One branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "73cec59a-29a6-4103-bac3-ba8112fed4aa",
          "name": "returns-all-of-the-capital-one-branches",
          "request": {
            "url": "http://api.reimaginebanking.com/branches",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all of the Capital One branches"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae98cd2c-e8db-4836-aa79-1fdb11e67c90"
            }
          ]
        }
      ]
    }
  ]
}