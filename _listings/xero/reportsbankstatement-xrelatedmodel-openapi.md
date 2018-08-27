---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting X-related-model Reports Bankstatement
  description: X-related-model reports bankstatement.
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Reports/BankStatement:
    get:
      summary: Get Reports Bankstatement
      description: Get reports bankstatement.
      operationId: getReportsBankstatement
      x-api-path-slug: reportsbankstatement-get
      parameters:
      - in: query
        name: bankAccountID
        description: bankAccountID e
      - in: query
        name: fromDate
        description: YYYY-MM-DD
      - in: query
        name: toDate
        description: YYYY-MM-DD
      responses:
        200:
          description: OK
      tags:
      - Reports
      - BankStatement
    x-related-model:
      summary: X-related-model Reports Bankstatement
      description: X-related-model reports bankstatement.
      operationId: x-related-modelReportsBankstatement
      x-api-path-slug: reportsbankstatement-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Reports
      - BankStatement
  /Reports/BankSummary:
    get:
      summary: Get Reports Banksummary
      description: Get reports banksummary.
      operationId: getReportsBanksummary
      x-api-path-slug: reportsbanksummary-get
      parameters:
      - in: query
        name: fromDate
        description: YYYY-MM-DD
      - in: query
        name: toDate
        description: YYYY-MM-DD
      responses:
        200:
          description: OK
      tags:
      - Reports
      - BankSummary
    x-related-model:
      summary: X-related-model Reports Banksummary
      description: X-related-model reports banksummary.
      operationId: x-related-modelReportsBanksummary
      x-api-path-slug: reportsbanksummary-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Reports
      - BankSummary
  /BankTransactions/{BankTransactionID}:
    get:
      summary: Get Bank Transactions Banktransaction
      description: Get banktransactions banktransaction.
      operationId: getBanktransactionsBanktransaction
      x-api-path-slug: banktransactionsbanktransactionid-get
      parameters:
      - in: path
        name: BankTransactionID
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
    post:
      summary: Post Bank Transactions Banktransaction
      description: Post banktransactions banktransaction.
      operationId: postBanktransactionsBanktransaction
      x-api-path-slug: banktransactionsbanktransactionid-post
      parameters:
      - in: path
        name: BankTransactionID
      - in: body
        name: BankTransactions
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
    x-related-model:
      summary: X-related-model Bank Transactions Banktransaction
      description: X-related-model banktransactions banktransaction.
      operationId: x-related-modelBanktransactionsBanktransaction
      x-api-path-slug: banktransactionsbanktransactionid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
  /BankTransactions/{BankTransactionID}/Attachments:
    get:
      summary: Get Bank Transactions Banktransaction Attachments
      description: Get banktransactions banktransaction attachments.
      operationId: getBanktransactionsBanktransactionAttachments
      x-api-path-slug: banktransactionsbanktransactionidattachments-get
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
  /BankTransactions/{BankTransactionID}/Attachments/{FileName}:
    get:
      summary: Get Bank Transactions Banktransaction Attachments Filename
      description: Get banktransactions banktransaction attachments filename.
      operationId: getBanktransactionsBanktransactionAttachmentsFilename
      x-api-path-slug: banktransactionsbanktransactionidattachmentsfilename-get
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
      - FileName
    post:
      summary: Post Bank Transactions Banktransaction Attachments Filename
      description: Post banktransactions banktransaction attachments filename.
      operationId: postBanktransactionsBanktransactionAttachmentsFilename
      x-api-path-slug: banktransactionsbanktransactionidattachmentsfilename-post
      parameters:
      - in: path
        name: BankTransactionID
        description: The Xero generated unique identifier for an bank transaction
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
      - BankTransactionID
      - Attachments
      - FileName
  /BankTransactions:
    get:
      summary: Get Bank Transactions
      description: Get banktransactions.
      operationId: getBanktransactions
      x-api-path-slug: banktransactions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
    post:
      summary: Post Bank Transactions
      description: Post banktransactions.
      operationId: postBanktransactions
      x-api-path-slug: banktransactions-post
      parameters:
      - in: body
        name: BankTransactions
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
    put:
      summary: Put Bank Transactions
      description: Put banktransactions.
      operationId: putBanktransactions
      x-api-path-slug: banktransactions-put
      parameters:
      - in: body
        name: BankTransactions
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
    x-related-model:
      summary: X-related-model Bank Transactions
      description: X-related-model banktransactions.
      operationId: x-related-modelBanktransactions
      x-api-path-slug: banktransactions-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransactions
  /BankTransfers/{BankTransferID}:
    get:
      summary: Get Banks Transfers
      description: Get banktransfers banktransfer.
      operationId: getBanktransfersBanktransfer
      x-api-path-slug: banktransfersbanktransferid-get
      parameters:
      - in: path
        name: BankTransferID
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
    x-related-model:
      summary: X-related-model Banks Transfers
      description: X-related-model banktransfers banktransfer.
      operationId: x-related-modelBanktransfersBanktransfer
      x-api-path-slug: banktransfersbanktransferid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
  /BankTransfers/{BankTransferID}/Attachments/{FileName}:
    get:
      summary: Get Banks Transfers Attachments Filename
      description: Get banktransfers banktransfer attachments filename.
      operationId: getBanktransfersBanktransferAttachmentsFilename
      x-api-path-slug: banktransfersbanktransferidattachmentsfilename-get
      parameters:
      - in: path
        name: BankTransferID
        description: The Xero generated unique identifier for an BankTransfer
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
      - Attachments
      - FileName
    post:
      summary: Post Banks Transfers Attachments Filename
      description: Post banktransfers banktransfer attachments filename.
      operationId: postBanktransfersBanktransferAttachmentsFilename
      x-api-path-slug: banktransfersbanktransferidattachmentsfilename-post
      parameters:
      - in: path
        name: BankTransferID
        description: The Xero generated unique identifier for a BankTransfer
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
      - BankTransferID
      - Attachments
      - FileName
  /BankTransfers:
    get:
      summary: Get Banks Transfers
      description: Get banktransfers.
      operationId: getBanktransfers
      x-api-path-slug: banktransfers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
    put:
      summary: Put Banks Transfers
      description: Put banktransfers.
      operationId: putBanktransfers
      x-api-path-slug: banktransfers-put
      parameters:
      - in: body
        name: BankTransfers
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
    x-related-model:
      summary: X-related-model Banks Transfers
      description: X-related-model banktransfers.
      operationId: x-related-modelBanktransfers
      x-api-path-slug: banktransfers-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - BankTransfers
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