---
swagger: "2.0"
x-collection-name: aWhere
x-complete: 0
info:
  title: aWhere Get Crops
  description: |-
    ####Request
    This API call returns the list of currently available crops in the aWhere platform.

    [Crops Documentation](http://developer.awhere.com/api/reference/crops).


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  version: 1.0.0
host: api.awhere.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/agronomics/fields/field1/agronomicvalues/2015-08-01,2015-08-03:
    get:
      summary: Agronomic Values & Accumulations
      description: "####Request\nThis API call gets calculated agronomics and accumulations
        at a field location. \n\nThe URL used here will get the values for a certain
        range of days. This is a very flexible API and so you're encouraged to review
        the [Agronomics Documentation](http://developer.awhere.com/api/reference/agronomics/values).\n\n_Tip:
        Remember to use a field ID that exists in your account. By default, this collection
        uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses
        the security Access Token that is retrieved with the \"Get a Token\" request.
        If you run that request first, it will save a token to Postman and this API
        will use it automatically. You can also see where the token should normally
        go by clicking the \"Headers\" tab below. The Authorization header holds the
        token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2AgronomicsFieldsField1Agronomicvalues2015080120150803Get
      x-api-path-slug: v2agronomicsfieldsfield1agronomicvalues2015080120150803-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Agronomic
      - Values
      - '&'
      - Accumulations
  /v2/agronomics/fields/field1/agronomicnorms/08-01,08-03/years/2010,2014:
    get:
      summary: Agronomic Norms
      description: "####Request\nThis API call gets the long term averages for agronomic
        values and accumulations at a field location. \n\nThe URL used here will get
        the values for a certain range of days over a certain range of years. This
        is a very flexible API and so you're encouraged to review the [Agronomics
        Documentation](http://developer.awhere.com/api/reference/agronomics/norms).\n\n_Tip:
        Remember to use a field ID that exists in your account. By default, this collection
        uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses
        the security Access Token that is retrieved with the \"Get a Token\" request.
        If you run that request first, it will save a token to Postman and this API
        will use it automatically. You can also see where the token should normally
        go by clicking the \"Headers\" tab below. The Authorization header holds the
        token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2AgronomicsFieldsField1Agronomicnorms08010803Years20102014Get
      x-api-path-slug: v2agronomicsfieldsfield1agronomicnorms08010803years20102014-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Agronomic
      - Norms
  /v2/fields:
    get:
      summary: Get Fields List
      description: "####Request\nThis API call retrieves the list of fields in your
        account. \n\n[Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2FieldsGet
      x-api-path-slug: v2fields-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Fields
      - List
    post:
      summary: Create a Field
      description: "####Request\nThis API call creates a field location in your account.
        Be sure to change the body payload. \n\n[Create Fields Documentation](http://developer.awhere.com/api/reference/fields/create-field)\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2FieldsPost
      x-api-path-slug: v2fields-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Field
  /v2/fields/field1:
    get:
      summary: Get a Single Field by ID
      description: |-
        ####Request
        This API call retrieves a single field by ID.

        [Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2FieldsField1Get
      x-api-path-slug: v2fieldsfield1-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Single
      - Field
      - By
      - ID
    patch:
      summary: Update Field
      description: |-
        ####Request
        This API call shows how to update the farm ID on a field location. You can also change the name.

        [Update Field Documentation](http://developer.awhere.com/api/reference/fields/update-field)


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2FieldsField1Patch
      x-api-path-slug: v2fieldsfield1-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Field
  /v2/agronomics/fields/field1/plantings:
    get:
      summary: Get Plantings List for a Field
      description: "####Request\nThis API call retrieves the list of plantings for
        a specific field in your account. \n\n[Get Plantings Documentation](http://developer.awhere.com/api/reference/plantings/get-plantings)\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2AgronomicsFieldsField1PlantingsGet
      x-api-path-slug: v2agronomicsfieldsfield1plantings-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Plantings
      - Lista
      - Field
    post:
      summary: Create a Planting
      description: "####Request\nThis API call creates a planting for a specific field
        in your account. \n\n__Note:__ You should at least change the dates in the
        request body.\n\n[Create Planting Documentation](http://developer.awhere.com/api/reference/plantings/create)\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2AgronomicsFieldsField1PlantingsPost
      x-api-path-slug: v2agronomicsfieldsfield1plantings-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Planting
  /v2/agronomics/fields/field1/plantings/current:
    patch:
      summary: Update Part of a Planting
      description: |-
        ####Request
        This API call shows how to update only a couple of fields in a planting instead of having to update the entire object.

        __Note:__ You probably what to change the date in the request body.

        [Update Planting Documentation](http://developer.awhere.com/api/reference/plantings/update)


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2AgronomicsFieldsField1PlantingsCurrentPatch
      x-api-path-slug: v2agronomicsfieldsfield1plantingscurrent-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Part
      - Of
      - Planting
  /v2/agronomics/crops:
    get:
      summary: Get Crops
      description: |-
        ####Request
        This API call returns the list of currently available crops in the aWhere platform.

        [Crops Documentation](http://developer.awhere.com/api/reference/crops).


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2AgronomicsCropsGet
      x-api-path-slug: v2agronomicscrops-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Crops
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