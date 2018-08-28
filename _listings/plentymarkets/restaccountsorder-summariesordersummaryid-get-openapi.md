---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get an order summary by the order summary ID
  description: Gets an order summary. The ID of the order summary must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/order_summaries:
    post:
      summary: Create an order summary
      description: Create an order summary.
      operationId: postRestAccountsOrderSummaries
      x-api-path-slug: restaccountsorder-summaries-post
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
  /rest/accounts/order_summaries/contacts/{contactId}:
    get:
      summary: Get an order summary by the contact ID
      description: Gets an order summary. The ID of the contact must be specified.
      operationId: getRestAccountsOrderSummariesContactsContact
      x-api-path-slug: restaccountsorder-summariescontactscontactid-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
      - By
      - Contact
      - ID
  /rest/accounts/order_summaries/orders/{addressId}:
    get:
      summary: Get an order summary by the address ID
      description: Gets an order summary. The ID of the address must be specified.
      operationId: getRestAccountsOrderSummariesOrdersAddress
      x-api-path-slug: restaccountsorder-summariesordersaddressid-get
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
      - By
      - Address
      - ID
  /rest/accounts/order_summaries/{orderSummaryId}:
    delete:
      summary: Delete an order summary
      description: Deletes an order summary. The ID of the order summary must be specified.
      operationId: deleteRestAccountsOrderSummariesOrdersummary
      x-api-path-slug: restaccountsorder-summariesordersummaryid-delete
      parameters:
      - in: path
        name: orderSummaryId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
    get:
      summary: Get an order summary by the order summary ID
      description: Gets an order summary. The ID of the order summary must be specified.
      operationId: getRestAccountsOrderSummariesOrdersummary
      x-api-path-slug: restaccountsorder-summariesordersummaryid-get
      parameters:
      - in: path
        name: orderSummaryId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
      - By
      - Order
      - Summary
      - ID
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