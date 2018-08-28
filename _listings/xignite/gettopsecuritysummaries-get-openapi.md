---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global News Get Top Security Summaries
  description: Returns all headline summaries that were published today for a given
    security.
  version: 1.0.0
host: globalnews.xignite.com
basePath: xGlobalNews.xml/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetRecommendationSummaryRange:
    get:
      summary: Get Recommendation Summary Range
      description: Get Recommendation Summaries in Range
      operationId: GetRecommendationSummaryRange
      x-api-path-slug: getrecommendationsummaryrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Recommendation
      - Summary
      - Range
  /GetLatestRecommendationSummaries:
    get:
      summary: Get Latest Recommendation Summaries
      description: Get Latest Recommendation Summary
      operationId: GetLatestRecommendationSummaries
      x-api-path-slug: getlatestrecommendationsummaries-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Recommendation
      - Summaries
  /GetRecommendationSummaries:
    get:
      summary: Get Recommendation Summaries
      description: Get Recommendation Summaries on AsOfDate
      operationId: GetRecommendationSummaries
      x-api-path-slug: getrecommendationsummaries-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Recommendation
      - Summaries
  /GetTopSecuritySummaries:
    get:
      summary: Get Top Security Summaries
      description: Returns all headline summaries that were published today for a
        given security.
      operationId: GetTopSecuritySummaries
      x-api-path-slug: gettopsecuritysummaries-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Top
      - Security
      - Summaries
  /GetTopReleaseSummariesBySecurity:
    get:
      summary: Get Top Release Summaries By Security
      description: Return the top press releases summaries for a security.
      operationId: GetTopReleaseSummariesBySecurity
      x-api-path-slug: gettopreleasesummariesbysecurity-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Top
      - Release
      - Summaries
      - Security
  /GetTopMarketSummaries:
    get:
      summary: Get Top Market Summaries
      description: Return the top market summaries.
      operationId: GetTopMarketSummaries
      x-api-path-slug: gettopmarketsummaries-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Top
      - Market
      - Summaries
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