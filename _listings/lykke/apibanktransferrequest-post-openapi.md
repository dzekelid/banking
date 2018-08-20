---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Banktransferrequest
  version: 1.0.0
  description: Add api banktransferrequest.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/BankCardPaymentUrl:
    post:
      summary: Add API Bankcardpaymenturl
      description: Add api bankcardpaymenturl.
      operationId: ApiBankCardPaymentUrlPost
      x-api-path-slug: apibankcardpaymenturl-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: input
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bankcardpaymenturl
  /api/BankCardPaymentUrlFormValues:
    get:
      summary: Get API Bankcardpaymenturlformvalues
      description: Get api bankcardpaymenturlformvalues.
      operationId: ApiBankCardPaymentUrlFormValuesGet
      x-api-path-slug: apibankcardpaymenturlformvalues-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Bankcardpaymenturlformvalues
  /api/BankTransferRequest:
    post:
      summary: Add API Banktransferrequest
      description: Add api banktransferrequest.
      operationId: ApiBankTransferRequestPost
      x-api-path-slug: apibanktransferrequest-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: transferReq
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Banktransferrequest
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---