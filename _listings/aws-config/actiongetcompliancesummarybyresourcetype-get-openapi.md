---
swagger: "2.0"
x-collection-name: AWS Config
x-complete: 0
info:
  title: AWS Config API Get Compliance Summary By Resource Type
  version: 1.0.0
  description: Returns the number of resources that are compliant and the number that
    are noncompliant.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetComplianceSummaryByConfigRule:
    get:
      summary: Get Compliance Summary By Config Rule
      description: "Returns the number of AWS Config rules that are compliant and
        noncompliant, up to a\n\t\t\tmaximum of 25 for each."
      operationId: getComplianceSummaryByConfigRule
      x-api-path-slug: actiongetcompliancesummarybyconfigrule-get
      parameters:
      - in: query
        name: ComplianceSummary
        description: The number of AWS Config rules that are compliant and the number
          that arenoncompliant, up to a maximum of 25 for each
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compliance
  /?Action=GetComplianceSummaryByResourceType:
    get:
      summary: Get Compliance Summary By Resource Type
      description: Returns the number of resources that are compliant and the number
        that are noncompliant.
      operationId: getComplianceSummaryByResourceType
      x-api-path-slug: actiongetcompliancesummarybyresourcetype-get
      parameters:
      - in: query
        name: ResourceTypes
        description: Specify one or more resource types to get the number of resources
          that are compliant and the number that are noncompliant for each resource
          type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compliance
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