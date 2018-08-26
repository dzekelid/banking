{
  "info": {
    "name": "Capital One DevExchange Get all ATMs",
    "_postman_id": "5175f4c0-f37b-4a7f-a860-431a5b85f1c4",
    "description": "Returns all of the Capital One ATMs in the speified search area.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "0088c0b3-9972-4692-b106-e78da0a32bbc",
          "name": "returns-all-of-the-capital-one-atms-in-the-speified-search-area",
          "request": {
            "url": "http://api.reimaginebanking.com/atms?lat=%7B%7D&lng=%7B%7D&rad=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all of the Capital One ATMs in the speified search area"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b4ae599-f711-41b1-8d63-3f1905ffab9e"
            }
          ]
        }
      ]
    }
  ]
}