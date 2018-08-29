---
name: aWhere
x-slug: awhere
description: aWhere Ag Data Management harnesses agriculture analytics to create unprecedented
  visibility and insight from farm level to national policy. Learn more at aWhere.com!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
x-kinRank: "7"
x-alexaRank: "891345"
tags: aWhere
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/apis.md
specificationVersion: "0.14"
apis:
- name: aWhere API Platform - Agronomic Values & Accumulations
  x-api-slug: v2agronomicsfieldsfield1agronomicvalues2015080120150803-get
  description: "####Request\nThis API call gets calculated agronomics and accumulations
    at a field location. \n\nThe URL used here will get the values for a certain range
    of days. This is a very flexible API and so you're encouraged to review the [Agronomics
    Documentation](http://developer.awhere.com/api/reference/agronomics/values).\n\n_Tip:
    Remember to use a field ID that exists in your account. By default, this collection
    uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the
    security Access Token that is retrieved with the \"Get a Token\" request. If you
    run that request first, it will save a token to Postman and this API will use
    it automatically. You can also see where the token should normally go by clicking
    the \"Headers\" tab below. The Authorization header holds the token, replacing
    the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1agronomicvalues2015080120150803-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1agronomicvalues2015080120150803-get-openapi.md
- name: aWhere API Platform - Agronomic Norms
  x-api-slug: v2agronomicsfieldsfield1agronomicnorms08010803years20102014-get
  description: "####Request\nThis API call gets the long term averages for agronomic
    values and accumulations at a field location. \n\nThe URL used here will get the
    values for a certain range of days over a certain range of years. This is a very
    flexible API and so you're encouraged to review the [Agronomics Documentation](http://developer.awhere.com/api/reference/agronomics/norms).\n\n_Tip:
    Remember to use a field ID that exists in your account. By default, this collection
    uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the
    security Access Token that is retrieved with the \"Get a Token\" request. If you
    run that request first, it will save a token to Postman and this API will use
    it automatically. You can also see where the token should normally go by clicking
    the \"Headers\" tab below. The Authorization header holds the token, replacing
    the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1agronomicnorms08010803years20102014-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1agronomicnorms08010803years20102014-get-openapi.md
- name: aWhere API Platform - Get Fields List
  x-api-slug: v2fields-get
  description: "####Request\nThis API call retrieves the list of fields in your account.
    \n\n[Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2fields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2fields-get-openapi.md
- name: aWhere API Platform - Create a Field
  x-api-slug: v2fields-post
  description: "####Request\nThis API call creates a field location in your account.
    Be sure to change the body payload. \n\n[Create Fields Documentation](http://developer.awhere.com/api/reference/fields/create-field)\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2fields-post-openapi.md
- name: aWhere API Platform - Get a Single Field by ID
  x-api-slug: v2fieldsfield1-get
  description: |-
    ####Request
    This API call retrieves a single field by ID.

    [Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2fieldsfield1-get-openapi.md
- name: aWhere API Platform - Update Field
  x-api-slug: v2fieldsfield1-patch
  description: |-
    ####Request
    This API call shows how to update the farm ID on a field location. You can also change the name.

    [Update Field Documentation](http://developer.awhere.com/api/reference/fields/update-field)


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2fieldsfield1-patch-openapi.md
- name: aWhere API Platform - Get Plantings List for a Field
  x-api-slug: v2agronomicsfieldsfield1plantings-get
  description: "####Request\nThis API call retrieves the list of plantings for a specific
    field in your account. \n\n[Get Plantings Documentation](http://developer.awhere.com/api/reference/plantings/get-plantings)\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1plantings-get-openapi.md
- name: aWhere API Platform - Create a Planting
  x-api-slug: v2agronomicsfieldsfield1plantings-post
  description: "####Request\nThis API call creates a planting for a specific field
    in your account. \n\n__Note:__ You should at least change the dates in the request
    body.\n\n[Create Planting Documentation](http://developer.awhere.com/api/reference/plantings/create)\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1plantings-post-openapi.md
- name: aWhere API Platform - Update Part of a Planting
  x-api-slug: v2agronomicsfieldsfield1plantingscurrent-patch
  description: |-
    ####Request
    This API call shows how to update only a couple of fields in a planting instead of having to update the entire object.

    __Note:__ You probably what to change the date in the request body.

    [Update Planting Documentation](http://developer.awhere.com/api/reference/plantings/update)


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1plantingscurrent-patch-openapi.md
- name: aWhere API Platform - Get Crops
  x-api-slug: v2agronomicscrops-get
  description: |-
    ####Request
    This API call returns the list of currently available crops in the aWhere platform.

    [Crops Documentation](http://developer.awhere.com/api/reference/crops).


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicscrops-get-openapi.md
- name: aWhere API Platform - Get Models
  x-api-slug: v2agronomicsmodels-get
  description: |-
    ####Request
    This API call returns the list of currently available models in the aWhere platform.

    [Crops Documentation](http://developer.awhere.com/api/reference/models/get-models).


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsmodels-get-openapi.md
- name: aWhere API Platform - Get Model Details
  x-api-slug: v2agronomicsmodelsbarleygenericmsudetails-get
  description: "####Request\nThis API call returns the details about a particular
    model. Currently, growth stage models are available via the API, so the details
    are a list of the possible stages with GDD threshold information. \n\n[Model Details
    Documentation](http://developer.awhere.com/api/reference/models/details).\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsmodelsbarleygenericmsudetails-get-openapi.md
- name: aWhere API Platform - Get Model Results
  x-api-slug: v2agronomicsfieldsfield1modelsbarleygenericmsuresults-get
  description: "####Request\nThis API call returns the current results of a model
    based on the data provided for the identified field location. \n\n[Model Results
    Documentation](http://developer.awhere.com/api/reference/models/results).\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2agronomicsfieldsfield1modelsbarleygenericmsuresults-get-openapi.md
- name: aWhere API Platform - Daily Observations
  x-api-slug: v2weatherfieldsfield1observations-get
  description: "####Request\nThis API call gets the weather at a field location.\n\nThe
    default URL will get the last seven days of actual weather observations. You can
    add dates to the end of the URL to get the weather for a specific range of days,
    like so: \n\n`/v2/weather/fields/field1/observations/2015-08-01` gets a single
    day\n`/v2/weather/fields/field1/observations/2015-08-01,2015-08-15` gets everything
    from August 1-15\n\nYou can customize the response payload using query string
    parameters. Learn more in the [Daily Observations Documentation](http://developer.awhere.com/api/reference/weather/observations).\n\n_Tip:
    Remember to use a field ID that exists in your account. By default, this collection
    uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the
    security Access Token that is retrieved with the \"Get a Token\" request. If you
    run that request first, it will save a token to Postman and this API will use
    it automatically. You can also see where the token should normally go by clicking
    the \"Headers\" tab below. The Authorization header holds the token, replacing
    the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2weatherfieldsfield1observations-get-openapi.md
- name: aWhere API Platform - Forecasts
  x-api-slug: v2weatherfieldsfield1forecasts-get
  description: "####Request\nThis API call gets the forecast at a field location.\n\nWith
    the default configuration you'll get the hourly forecast for today +8 days. Add
    dates to the end of the URL to request only specific days, like so: \n\n`/v2/weather/fields/field1/forecasts/YYYY-MM-DD`
    returns a single day\n`/v2/weather/fields/field1/forecasts/YYYY-MM-DD,YYYY-MM-DD`
    returns a range of days\n\nYou can also use query string parameters to customize
    the payloads. Read the [Forecast Documentation](http://developer.awhere.com/api/reference/weather/forecast)
    for details.\n\n\n_Tip: Remember to use a field ID that exists in your account.
    By default, this collection uses a default field ID of 'field1'_\n\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2weatherfieldsfield1forecasts-get-openapi.md
- name: aWhere API Platform - Norms
  x-api-slug: v2weatherfieldsfield1norms08010815years20102015-get
  description: |-
    ####Request
    Use this API to calculate long-term averages for the weather for any set of days across any set of years (minumum 3). This is a very flexible API, and you're encouraged to review the [Weather Norms Documentation](http://developer.awhere.com/api/reference/weather/norms) for details.

    _Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_

    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2weatherfieldsfield1norms08010815years20102015-get-openapi.md
- name: aWhere API Platform - Current Conditions
  x-api-slug: v2weatherfieldsfield1currentconditions-get
  description: |-
    ####Request
    This API call provides a snapshot of recent weather using the weather station nearest to the field location.

    [Current Conditions Documentation](http://developer.awhere.com/api/reference/weather/current)

    _Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/v2weatherfieldsfield1currentconditions-get-openapi.md
- name: aWhere API Platform - Get a Token
  x-api-slug: oauthtoken-post
  description: "This is the first API call you will make any time you use the API
    \n(but you only need to use once per hour). This request will \nrequest a security
    access token and save it to Postman. Later \nAPI calls will use the token from
    Postman's saved variables. \n\n[Authentication Documentation](http://developer.awhere.com/api/authentication)\n\nPrior
    to using this API call you should load the aWhere Environment\nfile into Postman
    and change the settings to your API Key and Secret.\nYou can also see where the
    key and secret should go, or enter\nthem manually, by choosing the \"Authorization\"
    tab below, selecting\n\"Basic Auth,\" and then entering the key and secret as
    the username\nand password."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/awhere/master/_listings/awhere/oauthtoken-post-openapi.md
x-common:
- type: x-blog-rss
  url: http://blog.awhere.com/rss.xml
- type: x-github
  url: https://github.com/aWhereAPI
- type: x-website
  url: http://www.awhere.com
- type: x-api-gallery
  url: http://automox.api.gallery.streamdata.io
- type: x-api-stack
  url: http://awhere.stack.network
- type: x-blog
  url: http://blog.awhere.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/awhere
- type: x-developers
  url: http://developer.awhere.com/
- type: x-website
  url: http://awhere.com
- type: x-support
  url: http://www.awhere.com/services-and-support
- type: x-twitter
  url: https://twitter.com/aWhere
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---