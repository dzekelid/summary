---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 1
info:
  title: AWS Identity and Access Management API
  version: 1.0.0
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
---