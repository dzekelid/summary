---
swagger: "2.0"
x-collection-name: nFusion Solutions
x-complete: 0
info:
  title: nFusion API Get latest Spot Summary for requested metal ratios
  description: Get latest spot summary for requested metal ratios.
  contact:
    name: nFusion Solutions
    url: https://nfusionsolutions.com/contact
    email: support@nfusionsolutions.com
  version: 1.0.0
host: api.nfusionsolutions.biz
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v{version}/Currencies/summary/supported:
    get:
      summary: Get list of currency pairs supported by the Summary endpoint
      description: "Only the currency pairs in the direction noted can be used with
        the Summary endpoint.\r\nFor example: USD/CAD is not the same as CAD/USD"
      operationId: ApiV{versionCurrenciesSummarySupportedGet
      x-api-path-slug: apivversioncurrenciessummarysupported-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Currency
      - Pairs
      - Supported
      - By
      - Summary
      - Endpoint
  /api/v{version}/Currencies/summary:
    get:
      summary: Get latest Summary for requested currency pairs
      description: Current and daily summary information combined into a single quote
      operationId: ApiV{versionCurrenciesSummaryGet
      x-api-path-slug: apivversioncurrenciessummary-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: pairs
        description: comma separated list of currency pairs
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Summaryrequested
      - Currency
      - Pairs
  /api/v{version}/Metals/spot/ratio/summary:
    get:
      summary: Get latest Spot Summary for requested metal ratios
      description: Get latest spot summary for requested metal ratios.
      operationId: ApiV{versionMetalsSpotRatioSummaryGet
      x-api-path-slug: apivversionmetalsspotratiosummary-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: pairs
        description: comma separated list of metal pairs
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Spot
      - Summaryrequested
      - Metal
      - Ratios
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