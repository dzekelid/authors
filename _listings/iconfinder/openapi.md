swagger: "2.0"
x-collection-name: Iconfinder
x-complete: 1
info:
  title: IconFinder
  description: give-your-users-instant-access-to-more-than-300000-icons-
  termsOfService: https://developer.iconfinder.com/api/2.0/terms.html
  version: v2
host: api.iconfinder.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /authors/{authorID}:
    get:
      summary: Get author details
      description: Get details about a specific author identified by a unique ID.
      operationId: getAuthorsAuthor
      x-api-path-slug: authorsauthorid-get
      parameters:
      - in: path
        name: authors
        description: The ID of the author
      responses:
        200:
          description: OK
      tags:
      - Authors