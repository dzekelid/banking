{
  "info": {
    "name": "Capital One DevExchange Get withdrawal by id",
    "_postman_id": "94b2222a-cbff-4a72-99e2-e041f9b4e19b",
    "description": "Returns the withdrawal with the specific id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "8b0397f6-68b5-4af9-981a-c21a8a3e991e",
          "name": "returns-the-withdrawal-with-the-specific-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "withdrawals/:id"
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
            "description": "Returns the withdrawal with the specific id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca16ae4a-d074-4a44-a105-cfb1f1be75fd"
            }
          ]
        }
      ]
    }
  ]
}