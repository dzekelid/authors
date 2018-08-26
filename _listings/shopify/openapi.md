---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/articles/authors.json:
    get:
      summary: Get a list of all the authors of articles
      description: Get a list of all the authors of articles.
      operationId: getAdminArticlesAuthors.json
      x-api-path-slug: adminarticlesauthors-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Authors
      - Articles
---