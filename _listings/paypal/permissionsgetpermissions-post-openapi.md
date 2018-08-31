---
swagger: "2.0"
x-collection-name: PayPal
x-complete: 0
info:
  title: Paypal Get Permissions
  description: Use the GetPermissons API operation to obtain the permissions associated
    with an access token.
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Permissions/GetAdvancedPersonalData:
    post:
      summary: Get Advanced Personal Data
      description: Use the GetAdvancedPersonalData API operation to obtain sensitive
        personal data for an account holder.
      operationId: Permissions.GetAdvancedPersonalData.post
      x-api-path-slug: permissionsgetadvancedpersonaldata-post
      responses:
        200:
          description: OK
      tags:
      - Payments
      - Profiles
  /Permissions/GetBasicPersonalData:
    post:
      summary: Get Basic Personal Data
      description: Use the GetBasicPersonalData API operation to obtain basic personal
        data for an account holder.
      operationId: Permissions.GetBasicPersonalData.post
      x-api-path-slug: permissionsgetbasicpersonaldata-post
      responses:
        200:
          description: OK
      tags:
      - Payments
      - Profiles
  /Permissions/CancelPermissions:
    post:
      summary: Cancel Permissions
      description: Use the CancelPermissions API operation to cancel access to a set
        of permissions.
      operationId: Permissions.CancelPermissions.post
      x-api-path-slug: permissionscancelpermissions-post
      responses:
        200:
          description: OK
      tags:
      - Payments
      - Permissions
  /Permissions/GetPermissions:
    post:
      summary: Get Permissions
      description: Use the GetPermissons API operation to obtain the permissions associated
        with an access token.
      operationId: Permissions.GetPermissions.post
      x-api-path-slug: permissionsgetpermissions-post
      responses:
        200:
          description: OK
      tags:
      - Payments
      - Permissions
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