---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Historical Get Top Gainers By Exchange
  description: This operation returns quote information about the top gaining equities
    for the requested exchange.
  version: 1.0.0
host: www.xignite.com
basePath: xGlobalHistorical.json/XigniteGlobalHistorical
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetTopDelayedFutures:
    get:
      summary: Get Top Delayed Futures
      description: Returns delayed quotes for a given number of contract (front-future
        first) for a commodity.
      operationId: postGettopdelayedfutures
      x-api-path-slug: gettopdelayedfutures-get
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
      - Delayed
      - Futures
  /GetTopIndustryHeadlines:
    get:
      summary: Get Top Industry Headlines
      description: Return the top press releases for an industry.
      operationId: postGettopindustryheadlines
      x-api-path-slug: gettopindustryheadlines-get
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
      - Industry
      - Headlines
  /GetTopMoversByExchange:
    get:
      summary: Get Top Movers By Exchange
      description: This operation returns quote information about the top moving equities
        for the requested exchange.
      operationId: postGettopmoversbyexchange
      x-api-path-slug: gettopmoversbyexchange-get
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
      - Movers
      - By
      - Exchange
  /GetTopGainersByExchange:
    get:
      summary: Get Top Gainers By Exchange
      description: This operation returns quote information about the top gaining
        equities for the requested exchange.
      operationId: postGettopgainersbyexchange
      x-api-path-slug: gettopgainersbyexchange-get
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
      - Gainers
      - By
      - Exchange
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