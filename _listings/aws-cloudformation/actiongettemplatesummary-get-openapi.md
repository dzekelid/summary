---
swagger: "2.0"
x-collection-name: AWS CloudFormation
x-complete: 0
info:
  title: AWS CloudFormation API Get Template Summary
  version: 1.0.0
  description: Returns information about a new or existing template.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetTemplateSummary:
    get:
      summary: Get Template Summary
      description: Returns information about a new or existing template.
      operationId: getTemplateSummary
      x-api-path-slug: actiongettemplatesummary-get
      parameters:
      - in: query
        name: StackName
        description: The name or the stack ID that is associated with the stack, which
          are not always interchangeable
        type: string
      - in: query
        name: TemplateBody
        description: Structure containing the template body with a minimum length
          of 1 byte and a maximum length of 51,200 bytes
        type: string
      - in: query
        name: TemplateURL
        description: Location of file containing the template body
        type: string
      responses:
        200:
          description: OK
      tags:
      - Templates
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