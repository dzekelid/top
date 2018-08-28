---
swagger: "2.0"
x-collection-name: Hacker News
x-complete: 0
info:
  title: Hacker News Returns the current top 100 stories.
  description: Returns the current top 100 stories.
  version: 1.0.0
host: hacker-news.firebaseio.com
basePath: /v0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /topstories.json:
    get:
      summary: Returns the current top 100 stories.
      description: Returns the current top 100 stories.
      operationId: get_top_stories
      x-api-path-slug: topstories-json-get
      responses:
        200:
          description: Successful response
      tags:
      - Links
      - Stories
      - Top
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