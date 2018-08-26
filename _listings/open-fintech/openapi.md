---
swagger: "2.0"
x-collection-name: Open FinTech
x-complete: 1
info:
  title: Open FinTech
  description: openfintech-io-is-an-open-database-that-comprises-of-standardized-primary-data-for-fintech-industry--it-contains-such-information-as-geolocation-data-countries-cities-regions-organizations-currencies-national-digital-virtual-crypto-banks-digital-exchangers-payment-providers-psp-payment-methods-etc-it-is-created-for-communication-of-crossintegrated-microservices-on-one-language--this-is-achieved-through-standardization-of-entity-identifiers-that-are-used-to-exchange-information-among-different-services-
  version: "2017-08-24"
host: api.openfintech.io
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /banks:
    get:
      summary: List of banks
      description: Returns list of banks. Each object contains general information
        about bank such as name and status, also information about bank details and
        related link to main organization.
      operationId: banks.get
      x-api-path-slug: banks-get
      parameters:
      - in: query
        name: filter[sort_code]
        description: Filtering by banks code
      - in: query
        name: filter[status]
        description: Filtration by status
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || code
          | -code || status | -status || sort_code | -sort_code |
      responses:
        200:
          description: OK
      tags:
      - Banks
  /banks/{id}:
    get:
      summary: Bank by ID
      description: Returns bank with specific ID.
      operationId: banks.id.get
      x-api-path-slug: banksid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Banks
---