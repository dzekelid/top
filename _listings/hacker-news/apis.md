---
name: Hacker News
x-slug: hacker-news
description: Hacker News is a social news website focusing on computer science and
  entrepreneurship. It is run by Paul Grahams investment fund and startup incubator,
  Y Combinator.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hn-246x0w.jpg
x-kinRank: "7"
x-alexaRank: ""
tags: Top
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/hacker-news/apis.md
specificationVersion: "0.14"
apis:
- name: Hacker News - Returns the current top 100 stories.
  x-api-slug: topstories-json-get
  description: Returns the current top 100 stories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hn-246x0w.jpg
  humanURL: https://news.ycombinator.com/
  baseURL: https://hacker-news.firebaseio.com//v0
  tags: Links, Bookmarks, Curation, SDIO Syndication, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/hacker-news/topstories-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/hacker-news/topstories-json-get-openapi.md
x-common:
- type: x-twitter
  url: https://twitter.com/newsycombinator
- type: x-api-gallery
  url: http://gumroad.api.gallery.streamdata.io
- type: x-api-stack
  url: http://hacker.news.stack.network
- type: x-developer
  url: https://github.com/HackerNews/API
- type: x-github
  url: https://github.com/HackerNews
- type: x-website
  url: https://news.ycombinator.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---