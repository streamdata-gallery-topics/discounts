swagger: "2.0"
x-collection-name: Square
x-complete: 1
info:
  title: Square Connect
  description: client-library-for-accessing-the-square-connect-apis
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{location_id}/discounts:
    get:
      summary: Lists all of a location's discounts.
      description: Lists all of a location's discounts.
      operationId: ListDiscounts
      x-api-path-slug: v1location-iddiscounts-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list categories for
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Of
      - Locations
      - Discounts