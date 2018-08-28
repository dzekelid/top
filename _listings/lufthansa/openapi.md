swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
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