---
swagger: "2.0"
x-collection-name: NewsCred
x-complete: 0
info:
  title: News Cred Author
  description: Returns an author that has written content available via this API.
  version: v1
host: api.newscred.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  author/:
    get:
      summary: Author
      description: Returns an author that has written content available via this API.
      operationId: getAuthor
      x-api-path-slug: author-get
      parameters:
      - in: query
        name: access_key
        description: Unique API access key
      responses:
        200:
          description: OK
      tags:
      - Author
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