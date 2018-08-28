---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 0
info:
  title: LH Partner Top OND
  version: "1.0"
  description: Returns LH Top routes per country or across all countries
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /offers/ond/top:
    get:
      summary: Top OND
      description: Returns LH Top routes per country or across all countries
      operationId: offers.ond.top.get
      x-api-path-slug: offersondtop-get
      parameters:
      - in: header
        name: Accept
        description: 'Mandatory http header:  application/xml or application/json'
      - in: query
        name: catalogues
        description: Carrier for which the OND will be retrieved (e
      - in: query
        name: origin
        description: Enter the origin country code (e
      responses:
        200:
          description: OK
      tags:
      - Top
      - OND
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