---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Describe Stack Summary
  version: 1.0.0
  description: |-
    Describes the number of layers and apps in a specified stack, and the number of instances in
          each state, such as running_setup or online.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeStackSummary:
    get:
      summary: Describe Stack Summary
      description: |-
        Describes the number of layers and apps in a specified stack, and the number of instances in
              each state, such as running_setup or online.
      operationId: describeStackSummary
      x-api-path-slug: actiondescribestacksummary-get
      parameters:
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Stack
      - Summary
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