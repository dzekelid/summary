---
swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 1
info:
  title: Broadleaf Commerce API
  description: the-default-broadleaf-commerce-apis
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /orders/summary:
    get:
      summary: Get Orders Summary
      description: Get orders summary.
      operationId: getOrdersSummary
      x-api-path-slug: orderssummary-get
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Summary
---