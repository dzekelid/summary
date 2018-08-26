---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
    get:
      summary: List order summaries
      description: List order summaries.
      operationId: getRestAccountsOrderSummaries
      x-api-path-slug: restaccountsorder-summaries-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Order
      - Summaries
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
    put:
      summary: Update an order summary
      description: Updates an order summary. The ID of the order summary must be specified.
      operationId: putRestAccountsOrderSummariesOrdersummary
      x-api-path-slug: restaccountsorder-summariesordersummaryid-put
      parameters:
      - in: path
        name: orderSummaryId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
  /rest/orders/documents/accounting_summary:
    get:
      summary: List document accounting summaries
      description: Lists document accounting summaries. A document accounting summary
        is saved along with each reversal document (for invoice and credit note).
        It contains accounting information about the order for this point in time.
        The summary is saved because an order can be updated after a reversal_document
        is generated. The information about the order before the update is needed
        for accounting.
      operationId: getRestOrdersDocumentsAccountingSummary
      x-api-path-slug: restordersdocumentsaccounting-summary-get
      parameters:
      - in: query
        name: createdAtFrom
        description: Get entries with createdAt date after this date
      - in: query
        name: createdAtTo
        description: Get entries with createdAt date before this date
      - in: query
        name: documentType
        description: The document type
      - in: query
        name: itemsPerPage
        description: The number of summaries to be displayed per page
      - in: query
        name: orderId
        description: The ID of the order
      - in: query
        name: page
        description: The page to get
      responses:
        200:
          description: OK
      tags:
      - List
      - Document
      - Accounting
      - Summaries
---