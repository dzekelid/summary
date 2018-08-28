swagger: "2.0"
x-collection-name: AWS CloudFormation
x-complete: 1
info:
  title: AWS CloudFormation API
  version: 1.0.0
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