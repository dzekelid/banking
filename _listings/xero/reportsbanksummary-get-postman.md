{
  "info": {
    "name": "Clarity Accounting Get Reports Banksummary",
    "_postman_id": "ccd1632c-7b94-4263-9806-ecabb72ff0e4",
    "description": "Get reports banksummary.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Reports",
      "item": [
        {
          "id": "b5de57cb-02a0-4337-9c85-3b3d9e08b03f",
          "name": "getReportsBankstatement",
          "request": {
            "url": "http://api.xero.com/api.xro/2.0/Reports/BankStatement?bankAccountID=%7B%7D&fromDate=%7B%7D&toDate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get reports bankstatement."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d4bf36b-5e6a-4348-9ca5-92775f6786ac"
            }
          ]
        },
        {
          "id": "e0cd1f9a-beb4-4373-b62f-9083eb9a0c65",
          "name": "getReportsBanksummary",
          "request": {
            "url": "http://api.xero.com/api.xro/2.0/Reports/BankSummary?fromDate=%7B%7D&toDate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get reports banksummary."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1069532-e90f-48bf-aeec-eae947973144"
            }
          ]
        }
      ]
    }
  ]
}