---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 0
info:
  title: Capital One DevExchange Get all ATMs
  description: Returns all of the Capital One ATMs in the speified search area.
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /atms:
    get:
      summary: Get all ATMs
      description: Returns all of the Capital One ATMs in the speified search area.
      operationId: returns-all-of-the-capital-one-atms-in-the-speified-search-area
      x-api-path-slug: atms-get
      parameters:
      - in: query
        name: lat
        description: Latitude of where youre looking for an ATM
      - in: query
        name: lng
        description: Longitude of where youre looking for an ATM
      - in: query
        name: rad
        description: Search radius in miles
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Atms
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