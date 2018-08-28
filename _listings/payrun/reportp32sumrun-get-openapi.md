---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Runs the P32 summary report
  description: Returns the result of the executed P32 summary report for the given
    query parameters
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Report/P11SUM/run:
    get:
      summary: Runs the P11 summary report
      description: Returns the result of the executed P11 summary report for the given
        query parameters
      operationId: GetP11SummaryReportOutput
      x-api-path-slug: reportp11sumrun-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: query
        name: EmployerKey
        description: The employer unique key
      - in: query
        name: PayScheduleKey
        description: The pay schedule unique key
      - in: query
        name: TaxPeriod
        description: The tax period number
      - in: query
        name: TaxYear
        description: The tax year
      responses:
        200:
          description: OK
      tags:
      - Runs
      - P11
      - Summary
      - Report
  /Report/P32SUM/run:
    get:
      summary: Runs the P32 summary report
      description: Returns the result of the executed P32 summary report for the given
        query parameters
      operationId: GetP32SummaryNetReportOutput
      x-api-path-slug: reportp32sumrun-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: query
        name: EmployerKey
        description: The employer unique key
      - in: query
        name: TaxYear
        description: The tax year
      responses:
        200:
          description: OK
      tags:
      - Runs
      - P32
      - Summary
      - Report
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