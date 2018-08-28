---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Event Tentatively Accept
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: meeventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /users/{id | userPrincipalName}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnameeventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /groups/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: groupsideventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /me/calendar/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendareventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /users/{id | userPrincipalName}/calendar/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendareventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
  /groups/{id}/calendar/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: groupsidcalendareventsidtentativelyaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Tentatively
      - Accept
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