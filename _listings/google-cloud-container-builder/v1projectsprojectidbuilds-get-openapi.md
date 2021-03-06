---
swagger: "2.0"
x-collection-name: Google Cloud Container Builder
x-complete: 0
info:
  title: Google Cloud Container Builder API Get Builds
  description: |-
    Lists previously requested builds.

    Previously requested builds may still be in-progress, or may have finished
    successfully or unsuccessfully.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudbuild.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/projects/{projectId}/builds:
    get:
      summary: Get Builds
      description: |-
        Lists previously requested builds.

        Previously requested builds may still be in-progress, or may have finished
        successfully or unsuccessfully.
      operationId: cloudbuild.projects.builds.list
      x-api-path-slug: v1projectsprojectidbuilds-get
      parameters:
      - in: query
        name: filter
        description: The raw filter text to constrain the results
      - in: query
        name: pageSize
        description: Number of results to return in the list
      - in: query
        name: pageToken
        description: Token to provide to skip to a particular spot in the list
      - in: path
        name: projectId
        description: ID of the project
      responses:
        200:
          description: OK
      tags:
      - Build
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