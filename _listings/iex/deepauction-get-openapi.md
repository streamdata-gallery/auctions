---
swagger: "2.0"
x-collection-name: IEX
x-complete: 0
info:
  title: IEX Trading API Auction
  description: For an example of an app that&rsquo;s using stats, see our IEX mobile
    app.
  termsOfService: https://iextrading.com/api-terms/
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.iextrading.com
basePath: /1.0
paths:
  /deep/auction:
    get:
      summary: Auction
      description: For an example of an app that&rsquo;s using stats, see our IEX
        mobile app.
      operationId: auction
      x-api-path-slug: deepauction-get
      parameters:
      - in: query
        name: symbols
        description: Parameter is required Value needs to be a comma-separated list
          of symbols (i
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Auctions
x-streamrank:
  polling_total_time_average: "0.16"
  polling_size_download_average: "11"
  streaming_total_time_average: "0.09"
  streaming_size_download_average: "5.5"
  change_yes: "2"
  change_no: "1796"
  time_percentage: "41"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-02-20"
  days_run: "4"
  minute_run: "0"
---