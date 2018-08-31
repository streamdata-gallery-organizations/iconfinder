---
swagger: "2.0"
x-collection-name: Iconfinder
x-complete: 0
info:
  title: Icon Finder Search for icons
  description: Search through icons by various criteria. The returned list of icons
    is ordered descendingly by popularit
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
  /categories:
    get:
      summary: List all categories
      description: List all categories sorted ascendingly by their identifier.
      operationId: getCategories
      x-api-path-slug: categories-get
      parameters:
      - in: query
        name: after
        description: identifier of the last category received
      - in: query
        name: count
      responses:
        200:
          description: OK
      tags:
      - Categories
  /icons/search:
    get:
      summary: Search for icons
      description: Search through icons by various criteria. The returned list of
        icons is ordered descendingly by popularit
      operationId: getIconsSearch
      x-api-path-slug: iconssearch-get
      parameters:
      - in: query
        name: category
      - in: query
        name: count
        description: Number of icons to include in the result
      - in: query
        name: license
        description: Filter by license scope
      - in: query
        name: maximum_size
        description: Maximum icon size to include in search result
      - in: query
        name: minimum_size
        description: Minimum icon size to include in search result
      - in: query
        name: offset
        description: Result offset
      - in: query
        name: premium
        description: Filter premium icons
      - in: query
        name: query
        description: Keyword to search by
      - in: query
        name: style
      - in: query
        name: vector
        description: Filter vector icons
      responses:
        200:
          description: OK
      tags:
      - Icons
      - Search
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