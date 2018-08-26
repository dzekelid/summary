---
swagger: "2.0"
x-collection-name: Taxamo
x-complete: 1
info:
  title: Taxamo
  description: taxamos-elegant-suite-of-apis-and-comprehensive-reporting-dashboard-enables-digital-merchants-to-easily-comply-with-eu-regulatory-requirements-on-tax-calculation-evidence-collection-tax-return-creation-and-data-storage-
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/reports/domestic/summary:
    get:
      summary: Calculate Domestic Summary
      description: Calculate domestic summary.
      operationId: getDomesticSummaryReport
      x-api-path-slug: apiv1reportsdomesticsummary-get
      parameters:
      - in: query
        name: country_code
        description: ISO 2-letter country code which will be used for determining
          which country is domestic
      - in: query
        name: currency_code
        description: ISO 3-letter currency code, e
      - in: query
        name: end_month
        description: Period end month in yyyy-MM format
      - in: query
        name: format
        description: Output format
      - in: query
        name: fx_date_type
        description: Which date should be used for FX
      - in: query
        name: start_month
        description: Period start month in yyyy-MM format
      responses:
        200:
          description: OK
      tags:
      - Calculate
      - Domestic
      - Summary
  /api/v1/settlement/summary/{quarter}:
    get:
      summary: Fetch Summary
      description: Fetch summary.
      operationId: getSettlementSummary
      x-api-path-slug: apiv1settlementsummaryquarter-get
      parameters:
      - in: query
        name: end_month
        description: Period end month in yyyy-MM format
      - in: query
        name: moss_country_code
        description: MOSS country code, used to determine currency
      - in: path
        name: quarter
        description: Quarter in yyyy-MM format
      - in: query
        name: start_month
        description: Period start month in yyyy-MM format
      - in: query
        name: tax_region
        description: Tax region key
      responses:
        200:
          description: OK
      tags:
      - Fetch
      - Summary
---