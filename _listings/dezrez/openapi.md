---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/offeraccepted:
    post:
      summary: Generates a correspondence any parties of the acceptance of an offer.  Uses
        default values where possible.
      description: Generates a correspondence any parties of the acceptance of an
        offer.  uses default values where possible..
      operationId: DocumentGeneration_OfferAcceptedLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationofferaccepted-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - Any
      - Parties
      - Of
      - Acceptance
      - Of
      - Offer
      - ""
      - ""
      - Uses
      - Default
      - Values
      - Where
      - Possible
---