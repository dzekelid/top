---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Releases Get Top Security Headlines
  description: Returns a given number of company headlines published most recently.
  version: v1
host: http://www.xignite.com/
basePath: xReleases.xml/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  GetTopMarketHeadlines/:
    get:
      summary: Get Top Market Headlines
      description: Returns a given number of market headlines published most recently.
      operationId: getGettopmarketheadlines
      x-api-path-slug: gettopmarketheadlines-get
      parameters:
      - in: query
        name: Count
        description: The number of news items to return
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Top
      - Market
      - Headlines
  GetTopSecurityHeadlines/:
    get:
      summary: Get Top Security Headlines
      description: Returns a given number of company headlines published most recently.
      operationId: getGettopsecurityheadlines
      x-api-path-slug: gettopsecurityheadlines-get
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Top
      - Security
      - Headlines
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