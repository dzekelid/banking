{
  "info": {
    "name": "Clarity Accounting X-related-model Reports Banksummary",
    "_postman_id": "12370f0d-2ace-4475-b532-9a48c3b737bd",
    "description": "X-related-model reports banksummary.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Reports",
      "item": [
        {
          "id": "559b1332-92d2-413b-ae49-e2d8594abd16",
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
              "id": "1531bbf6-ecaf-4ebf-8b23-d8ef53ba6813"
            }
          ]
        },
        {
          "id": "584d6ddd-f9d1-46ea-9a0f-f7e6536415d6",
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
              "id": "518c609a-3202-4ad1-87bb-9b7cc2ffdc60"
            }
          ]
        }
      ]
    }
  ]
}