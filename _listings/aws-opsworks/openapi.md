swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
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