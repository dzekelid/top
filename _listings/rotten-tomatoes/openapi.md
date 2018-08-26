---
swagger: "2.0"
x-collection-name: Rotten Tomatoes
x-complete: 1
info:
  title: Rotten Tomatoes
  description: test-our-api-services-using-io-docs-
  contact:
    name: Mike Ralphson
    url: https://github.com/mermade/mashery2openapi
    email: mike.ralphson@gmail.com
  version: "1.0"
host: api.rottentomatoes.com
basePath: /api/public/v1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /lists/dvds/top_rentals.json:
    get:
      summary: Get Lists Dvds Top Rentals
      description: Get lists dvds top rentals.json.
      operationId: getListsDvdsTopRentals.json
      x-api-path-slug: listsdvdstop-rentals-json-get
      parameters:
      - in: query
        name: country
        description: Provides localized data for the selected country (ISO 3166-1
          alpha-2) if available
      - in: query
        name: limit
        description: Limits the number of top rentals returned
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Dvds
      - Top
      - Rentals
---