---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Set Primary Bank Account for Accounting System
  version: 1.0.0
  description: Set primary bank account for accounting system.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/accountingsystem/setprimaryaccount:
    post:
      summary: Set Primary Bank Account for Accounting System
      description: Set primary bank account for accounting system.
      operationId: AccountingSystem_SetPrimarySystemBankAccountByid
      x-api-path-slug: apiaccountingsystemsetprimaryaccount-post
      parameters:
      - in: query
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Primary
      - Bank
      - AccountAccounting
      - System
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