{
  "info": {
    "name": "Capital One DevExchange Get purchase by id",
    "_postman_id": "884de699-2bca-4194-91b6-c8e9e13982c7",
    "description": "Returns the purchase with the specific id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "573a260f-8227-4943-a606-a39fc5e4ea55",
          "name": "returns-the-purchase-with-the-specific-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "purchases/:id"
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
            "description": "Returns the purchase with the specific id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ded80ff-ac2d-4f84-8ad5-d458030227f0"
            }
          ]
        }
      ]
    }
  ]
}