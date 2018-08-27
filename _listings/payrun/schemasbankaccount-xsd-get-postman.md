{
  "info": {
    "name": "Pay Run.IO Get the BankAccount schema",
    "_postman_id": "ae22b702-5556-446e-ad87-4e994771e6db",
    "description": "Returns the BankAccount schema object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "BankAccount",
      "item": [
        {
          "id": "0fb2b8dd-2295-4cf3-ba85-b812e7238f5d",
          "name": "GetBankAccountSchema",
          "request": {
            "url": "http://api.test.payrun.io/Schemas/BankAccount.xsd",
            "method": "GET",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the BankAccount schema object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82b32015-6c73-4a62-91b6-1f8868ebb7ee"
            }
          ]
        }
      ]
    }
  ]
}