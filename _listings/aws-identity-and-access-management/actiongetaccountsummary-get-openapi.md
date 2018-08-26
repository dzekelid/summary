---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Get Account Summary
  version: 1.0.0
  description: |-
    Retrieves information about IAM entity usage and IAM quotas in the AWS
          account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetAccountSummary:
    get:
      summary: Get Account Summary
      description: |-
        Retrieves information about IAM entity usage and IAM quotas in the AWS
              account.
      operationId: getAccountSummary
      x-api-path-slug: actiongetaccountsummary-get
      parameters:
      - in: query
        name: |-
          SummaryMap
                      , SummaryMap.entry.N.key (key), SummaryMapentry.N.value (value)
        description: A set of key value pairs containing information about IAM entity
          usage and IAM      quotas
        type: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
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