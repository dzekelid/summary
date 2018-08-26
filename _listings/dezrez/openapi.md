---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/account/{id}/invoiceoverview:
    post:
      summary: Get summary of an account based on invoice amounts allocated
      description: Get summary of an account based on invoice amounts allocated.
      operationId: Account_GetInvoiceOverviewByidBydataContract
      x-api-path-slug: apiaccountidinvoiceoverview-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Summary
      - Of
      - Account
      - Based
      - "On"
      - Invoice
      - Amounts
      - Ocated
  /api/branding/branch:
    get:
      summary: Gets a sumary all of the brands for a branch
      description: Gets a sumary all of the brands for a branch.
      operationId: Branding_GetBranch
      x-api-path-slug: apibrandingbranch-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Sumary
      - ""
      - Of
      - Brandsa
      - Branch
  /api/Branding:
    get:
      summary: Gets a sumary all of the brands for a agency
      description: Gets a sumary all of the brands for a agency.
      operationId: Branding_Get
      x-api-path-slug: apibranding-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Sumary
      - ""
      - Of
      - Brandsa
      - Agency
---