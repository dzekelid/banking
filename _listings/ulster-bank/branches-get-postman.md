{
  "info": {
    "name": "Ulster Bank Get Branches",
    "_postman_id": "b9989b7e-7ecc-4124-85d2-d861000afa47",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "d73dd254-fcce-4eb3-a078-d28cf4b4ddd1",
          "name": "getBranches",
          "request": {
            "url": "http://openapi.ulsterbank.co.uk/open-banking/v2.1/branches/",
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
              "id": "4ad73c8e-be50-400d-8844-3cbee415a84a"
            }
          ]
        }
      ]
    }
  ]
}