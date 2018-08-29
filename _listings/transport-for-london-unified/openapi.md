swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 1
info:
  title: Transport for London Unified
  description: our-unified-api-brings-together-data-across-all-modes-of-transport-into-a-single-restful-api--this-api-provides-access-to-the-most-highly-requested-realtime-and-status-infomation-across-all-the-modes-of-transport-in-a-single-and-consistent-way--access-to-the-developer-documentation-is-available-at-httpsapi-tfl-gov-uk
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Vehicle/EmissionSurcharge:
    get:
      summary: Vehicle  Emission Surcharge
      description: Gets the emissions surcharge compliance for the vehicle.
      operationId: Vehicle_GetEmissionsSurchargeCompliance
      x-api-path-slug: vehicleemissionsurcharge-get
      parameters:
      - in: query
        name: vrm
        description: The Vehicle Registration Mark
      responses:
        200:
          description: OK
      tags:
      - Vehicle
      - ""
      - Emission
      - Surcharge
  /Vehicle/UlezCompliance:
    get:
      summary: Vehicle  Ulez Compliance
      description: Gets the ulez surcharge compliance for the vehicle.
      operationId: Vehicle_GetUlezCompliance
      x-api-path-slug: vehicleulezcompliance-get
      parameters:
      - in: query
        name: vrm
        description: The Vehicle Registration Mark
      responses:
        200:
          description: OK
      tags:
      - Vehicle
      - ""
      - Ulez
      - Compliance
  /Vehicle/{ids}/Arrivals:
    get:
      summary: Vehicle s  Arrivals
      description: Gets the predictions for a given list of vehicle id's..
      operationId: Vehicle_Get
      x-api-path-slug: vehicleidsarrivals-get
      parameters:
      - in: path
        name: ids
        description: A comma-separated list of vehicle ids e
      responses:
        200:
          description: OK
      tags:
      - Vehicle
      - S
      - ""
      - Arrivals