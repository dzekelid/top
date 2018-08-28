---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global News Get Top Releases By Security
  description: Return the top press releases for a security.
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
      description: Get top industry headlines.
      operationId: GetTopIndustryHeadlines
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
  /GetTopLosersByExchange:
    get:
      summary: Get Top Losers By Exchange
      description: This operation returns quote information about the top losing equities
        for the requested exchange.
      operationId: postGettoplosersbyexchange
      x-api-path-slug: gettoplosersbyexchange-get
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
      - Losers
      - By
      - Exchange
  /GetTopReleasesBySecurity:
    get:
      summary: Get Top Releases By Security
      description: Return the top press releases for a security.
      operationId: GetTopReleasesBySecurity
      x-api-path-slug: gettopreleasesbysecurity-get
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
      - Releases
      - Security
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