swagger: "2.0"
x-collection-name: Hacker News
x-complete: 1
info:
  title: Hacker News
  description: phacker-news-apip
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