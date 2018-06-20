---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /me/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendarsideventsidtentativelyaccept-post
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
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidtentativelyaccept-post
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
  /me/calendargroup/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendargroupcalendarsideventsidtentativelyaccept-post
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
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidtentativelyaccept-post
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
  /me/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: mecalendargroupsidcalendarsideventsidtentativelyaccept-post
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
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept:
    post:
      summary: Event Tentatively Accept
      description: 'event: tentativelyAccept Tentatively accept the specified event.'
      operationId: Event:TentativelyAccept
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidtentativelyaccept-post
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
---