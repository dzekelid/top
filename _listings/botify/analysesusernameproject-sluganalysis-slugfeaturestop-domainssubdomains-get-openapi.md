---
swagger: "2.0"
x-collection-name: Botify
x-complete: 0
info:
  title: Botify Get Analyses Username Project Slug Analysis Slug Features Top Domains
    Subdomains
  description: Get analyses username project slug analysis slug features top domains
    subdomains.
  version: 1.0.0
host: api.botify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /analyses/{username}/{project_slug}/{analysis_slug}/features/top_domains/domains:
    get:
      summary: Get Analyses Username Project Slug Analysis Slug Features Top Domains
        Domains
      description: Get analyses username project slug analysis slug features top domains
        domains.
      operationId: getAnalysesUsernameProjectSlugAnalysisSlugFeaturesTopDomainsDomains
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturestop-domainsdomains-get
      parameters:
      - in: query
        name: page
        description: Page Number
      - in: query
        name: size
        description: Page Size
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Top
      - Domains
      - Domains
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Top
        Domains Domains
      description: Parameters analyses username project slug analysis slug features
        top domains domains.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesTopDomainsDomains
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturestop-domainsdomains-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Top
      - Domains
      - Domains
  /analyses/{username}/{project_slug}/{analysis_slug}/features/top_domains/subdomains:
    get:
      summary: Get Analyses Username Project Slug Analysis Slug Features Top Domains
        Subdomains
      description: Get analyses username project slug analysis slug features top domains
        subdomains.
      operationId: getAnalysesUsernameProjectSlugAnalysisSlugFeaturesTopDomainsSubdomains
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturestop-domainssubdomains-get
      parameters:
      - in: query
        name: page
        description: Page Number
      - in: query
        name: size
        description: Page Size
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Top
      - Domains
      - Subdomains
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