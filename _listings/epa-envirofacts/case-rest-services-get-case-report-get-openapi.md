---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Enforcement Case
    Search Enforcement Case Summary Report Search
  description: The get_case_report service endpoint returns a complex object of civil
    enforcement case details based on the provided case id.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 1.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dfr_rest_services.get_inspections:
    get:
      summary: Detailed Facility Report Inspections Summary Service
      description: This procedure obtains data for Enforcement and Compliance Summary
        Section of the Detailed Facility report.
      operationId: this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-
      x-api-path-slug: dfr-rest-services-get-inspections-get
      parameters:
      - in: query
        name: No Name
      responses:
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Inspections
      - Summary
      - Service
  /dfr_rest_services.get_enforcement_summary:
    get:
      summary: Detailed Facility Report Enforcement Summary Service
      description: This procedure obtains data for the Enforcement and Compliance
        Summary in the Facility Summary section of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti
      x-api-path-slug: dfr-rest-services-get-enforcement-summary-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Enforcement
      - Summary
      - Service
  /dfr_rest_services.get_compliance_summary:
    get:
      summary: Detailed Facility Report Compliance Summary Service
      description: This procedure obtains data for Compliance Summary Data in the
        Enforcement and Compliance Section of the Detailed Facility report.
      operationId: this-procedure-obtains-data-for-compliance-summary-data-in-the-enforcement-and-compliance-section-of
      x-api-path-slug: dfr-rest-services-get-compliance-summary-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Compliance
      - Summary
      - Service
  /eff_rest_services.get_summary_chart:
    get:
      summary: Summary Effluent Chart Service
      description: Summary of compliance status each outfall and parameter for one
        NPDES permit. Provides the current compliance status and overall compliance
        status for the date range of interest. This service supports the Summary Matrix
        on the Effluent Charts.
      operationId: summary-of-compliance-status-each-outfall-and-parameter-for-one-npdes-permit--provides-the-current-c
      x-api-path-slug: eff-rest-services-get-summary-chart-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Summary
      - Effluent
      - Chart
      - Service
  /case_rest_services.get_crcase_report:
    get:
      summary: Enforcement Criminal Case Summary Report Search
      description: The get_crcase_report service end point returns a complex object
        of criminal case detials based on the provided criminal case id.
      operationId: the-get-crcase-report-service-end-point-returns-a-complex-object-of-criminal-case-detials-based-on-t
      x-api-path-slug: case-rest-services-get-crcase-report-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: p_id
        description: Prosecution Summary Identifier
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Enforcement
      - Criminal
      - Case
      - Summary
      - Report
      - Search
  /case_rest_services.get_case_report:
    get:
      summary: Enforcement Case Summary Report Search
      description: The get_case_report service endpoint returns a complex object of
        civil enforcement case details based on the provided case id.
      operationId: the-get-case-report-service-endpoint-returns-a-complex-object-of-civil-enforcement-case-details-base
      x-api-path-slug: case-rest-services-get-case-report-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      - in: query
        name: p_id
        description: Case Number
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Enforcement
      - Case
      - Summary
      - Report
      - Search
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