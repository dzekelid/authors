swagger: "2.0"
x-collection-name: Spreaker
x-complete: 1
info:
  title: Spreaker API
  version: v1
host: api.spreaker.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/{user_id}/shows/author:
    get:
      summary: GEt Shows By Author
      description: ""
      operationId: getUserUserShowsAuthor
      x-api-path-slug: useruser-idshowsauthor-get
      parameters:
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - GEt
      - Shows
      - Author