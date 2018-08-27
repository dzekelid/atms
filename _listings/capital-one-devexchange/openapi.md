swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 1
info:
  title: Capital One DevExchange
  description: nessie-is-capital-ones-hackathon-api-that-gives-you-access-to-a-multitude-of-real-publicfacing-data--such-as-atm-and-bank-branch-locations--along-with-mock-customer-account-data--use-http-requests-to-set-up-peertopeer-transactions-simulate-a-weekly-paycheck-or-even-schedule-bills-for-customers-this-is-all-structured-in-a-way-that-resembles-how-we-actually-run-things-here-at-capital-one-
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
  /atms/{id}:
    get:
      summary: Get ATM by id
      description: Returns the ATM with the specific id
      operationId: returns-the-atm-with-the-specific-id
      x-api-path-slug: atmsid-get
      parameters:
      - in: path
        name: id
        description: ID of ATM that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Atms