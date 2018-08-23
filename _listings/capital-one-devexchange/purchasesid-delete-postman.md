{
  "info": {
    "name": "Capital One DevExchange Delete a specific existing purchase",
    "_postman_id": "3033836d-3842-48cf-9932-bd52caf8f39f",
    "description": "Deletes the specific purchase",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "53c0b3f6-f194-4475-9d7d-3fb8e865b191",
          "name": "deletes-the-specific-purchase",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specific purchase"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41bb2411-99ee-48df-b451-7f6fbdd883c8"
            }
          ]
        }
      ]
    }
  ]
}