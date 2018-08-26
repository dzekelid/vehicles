---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli List All Odometer Reports for a Vehicle
  description: List all odometer reports for a vehicle.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/vehicles:
    get:
      summary: List a Device's Vehicles
      description: List a device's vehicles.
      operationId: DevicesCf217c2dDf3c41f7B6108bc3e11b4b79VehiclesGet
      x-api-path-slug: devicescf217c2ddf3c41f7b6108bc3e11b4b79vehicles-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Devices
      - Vehicles
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/trips:
    get:
      summary: List All of a Vehicle's Trips
      description: List all of a vehicle's trips.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30TripsGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30trips-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Of
      - Vehicles
      - Trips
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/distances:
    get:
      summary: Get list of  a Vehicles Distances
      description: Get list of  a vehicles distances.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30DistancesGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30distances-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - ""
      - Vehicles
      - Distances
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometer_triggers:
    get:
      summary: List all Odometer Triggers for a Vehicle
      description: List all odometer triggers for a vehicle.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometerTriggersGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30odometer-triggers-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Odometer
      - Triggersa
      - Vehicle
  /vehicles/aa44769b-3c0a-4662-9bad-25481cf5198f:
    get:
      summary: Get Vehicle Details
      description: Get vehicle details.
      operationId: VehiclesAa44769b3c0a46629bad25481cf5198fGet
      x-api-path-slug: vehiclesaa44769b3c0a46629bad25481cf5198f-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Vehicle
      - Details
  /vehicles/428bc621-16e7-489b-a02a-eb98526d01ef/collisions:
    get:
      summary: Get a List of Collisions for a Vehicle
      description: Get a list of collisions for a vehicle.
      operationId: Vehicles428bc62116e7489bA02aEb98526d01efCollisionsGet
      x-api-path-slug: vehicles428bc62116e7489ba02aeb98526d01efcollisions-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Collisionsa
      - Vehicle
  /devices/821374c0-d6d8-11e3-9c1a-0800200c9a66/vehicles/_latest:
    get:
      summary: Get Device's Latest Vehicle
      description: Get device's latest vehicle.
      operationId: Devices821374c0D6d811e39c1a0800200c9a66VehiclesLatestGet
      x-api-path-slug: devices821374c0d6d811e39c1a0800200c9a66vehicles-latest-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Devices
      - Latest
      - Vehicle
  /vehicles/8480c5b7-6f3e-40b3-a78e-3555617d44b0/report_cards:
    get:
      summary: Report Cards for a Vehicle
      description: Report cards for a vehicle.
      operationId: Vehicles8480c5b76f3e40b3A78e3555617d44b0ReportCardsGet
      x-api-path-slug: vehicles8480c5b76f3e40b3a78e3555617d44b0report-cards-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Report
      - Cardsa
      - Vehicle
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometers:
    get:
      summary: List All Odometer Reports for a Vehicle
      description: List all odometer reports for a vehicle.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometersGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30odometers-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Odometer
      - Reportsa
      - Vehicle
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