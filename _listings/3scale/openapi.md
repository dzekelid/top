swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3scale Service Management API
  description: the-api-for-managing-3scale-services-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /stats/services/{service_id}/top_applications.{format}:
    get:
      summary: Service Top Applications
      description: Service top applications.
      operationId: service_ops
      x-api-path-slug: statsservicesservice-idtop-applications-format-get
      parameters:
      - in: path
        name: format
        description: Response format
      - in: query
        name: metric_name
        description: System name of metric for which to get data
      - in: query
        name: period
        description: 'Period, combined with since give the stats for the time range
          [since '
      - in: query
        name: provider_key
        description: Your api key with 3scale
      - in: path
        name: service_id
        description: id of the service
      - in: query
        name: since
        description: Time range start
      responses:
        200:
          description: OK
      tags:
      - Service
      - Top
      - Applications