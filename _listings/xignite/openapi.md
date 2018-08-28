swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
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