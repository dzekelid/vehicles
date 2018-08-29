---
name: Coord
x-slug: coord
description: Coord is a mobility company that creates seamless mobility and self-driving
  experiences today through deep integrations. The company offers bike-share API,
  Curbs API, Tolls API, Routing API and etc.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
x-kinRank: "7"
x-alexaRank: "1035226"
tags: Vehicles
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vehicles/master/_listings/coord/apis.md
specificationVersion: "0.14"
apis:
- name: Users API - Update the current user's vehicle
  x-api-slug: usercurrentvehicle-put
  description: |-
    Update the vehicle information associated with the currently logged in user.

    The request should contain a vehicle object:
    ```
      {
        "license_plate": {
          "text": "123abc",
          "country": "us",
          "subdivision": "ny"
        }
      }
    ```

    On success, the response will be the identical object:
    ```
      {
        "license_plate": {
          "text": "123abc",
          "country": "us",
          "subdivision": "ny"
        }
      }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/users
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vehicles/master/_listings/coord/usercurrentvehicle-put-openapi.md
- name: Users API - Update the current user's vehicle
  x-api-slug: usercurrentvehicle-put
  description: |-
    Update the vehicle information associated with the currently logged in user.

    The request should contain a vehicle object:
    ```
      {
        "license_plate": {
          "text": "123abc",
          "country": "us",
          "subdivision": "ny"
        }
      }
    ```

    On success, the response will be the identical object:
    ```
      {
        "license_plate": {
          "text": "123abc",
          "country": "us",
          "subdivision": "ny"
        }
      }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/users
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vehicles/master/_listings/coord/usercurrentvehicle-put-openapi.md
- name: Users API - Update the current user's vehicle
  x-api-slug: usercurrentvehicle-put
  description: |-
    Update the vehicle information associated with the currently logged in user.

    The request should contain a vehicle object:
    ```
      {
        "license_plate": {
          "text": "123abc",
          "country": "us",
          "subdivision": "ny"
        }
      }
    ```

    On success, the response will be the identical object:
    ```
      {
        "license_plate": {
          "text": "123abc",
          "country": "us",
          "subdivision": "ny"
        }
      }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/users
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vehicles/master/_listings/coord/usercurrentvehicle-put-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/coord
- type: x-blog-rss
  url: https://medium.com/feed/coord
- type: x-openapi
  url: https://jsapi.apiary.io/apis/coordprodsearchtolls.source
- type: x-api-gallery
  url: http://convertapi.api.gallery.streamdata.io
- type: x-api-stack
  url: http://coord.stack.network
- type: x-developer
  url: https://coord.co/docs/
- type: x-pricing
  url: https://coord.co/#pricing
- type: x-twitter
  url: https://twitter.com/coordcity
- type: x-website
  url: https://coord.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---