{
  "info": {
    "name": "Capital One DevExchange Get ATM by id",
    "_postman_id": "2ce1d261-bac4-4fcf-8872-91b1c50f80f4",
    "description": "Returns the ATM with the specific id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "c649d687-7381-4f91-9981-798afbc1dbe3",
          "name": "returns-the-atm-with-the-specific-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "atms/:id"
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
            "description": "Returns the ATM with the specific id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96bcdd49-12fe-4200-a236-f0e9b0428b01"
            }
          ]
        }
      ]
    }
  ]
}