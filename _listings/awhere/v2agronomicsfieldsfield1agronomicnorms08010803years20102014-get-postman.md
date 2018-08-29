{
  "info": {
    "name": "aWhere Agronomic Norms",
    "_postman_id": "10b080c3-612c-4e62-99d2-aee1869a552a",
    "description": "####Request\nThis API call gets the long term averages for agronomic values and accumulations at a field location. \n\nThe URL used here will get the values for a certain range of days over a certain range of years. This is a very flexible API and so you're encouraged to review the [Agronomics Documentation](http://developer.awhere.com/api/reference/agronomics/norms).\n\n_Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the security Access Token that is retrieved with the \"Get a Token\" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the \"Headers\" tab below. The Authorization header holds the token, replacing the \"{{aWhereAccessToken}}\" part.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Agriculture",
      "item": [
        {
          "id": "c6d84e37-39c5-4176-8cba-cc88a5d2154d",
          "name": "V2AgronomicsFieldsField1Agronomicvalues2015080120150803Get",
          "request": {
            "url": "http://api.awhere.com/v2/agronomics/fields/field1/agronomicvalues/2015-08-01,2015-08-03",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "####Request\nThis API call gets calculated agronomics and accumulations at a field location. \n\nThe URL used here will get the values for a certain range of days. This is a very flexible API and so you're encouraged to review the [Agronomics Documentation](http://developer.awhere.com/api/reference/agronomics/values).\n\n_Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the security Access Token that is retrieved with the \"Get a Token\" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the \"Headers\" tab below. The Authorization header holds the token, replacing the \"{{aWhereAccessToken}}\" part."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4300610f-2a1d-4753-9185-7a3f67c187a2"
            }
          ]
        },
        {
          "id": "2eb7a7ab-dd1d-4d57-bdab-00e8f4513c59",
          "name": "V2AgronomicsFieldsField1Agronomicnorms08010803Years20102014Get",
          "request": {
            "url": "http://api.awhere.com/v2/agronomics/fields/field1/agronomicnorms/08-01,08-03/years/2010,2014",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "####Request\nThis API call gets the long term averages for agronomic values and accumulations at a field location. \n\nThe URL used here will get the values for a certain range of days over a certain range of years. This is a very flexible API and so you're encouraged to review the [Agronomics Documentation](http://developer.awhere.com/api/reference/agronomics/norms).\n\n_Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the security Access Token that is retrieved with the \"Get a Token\" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the \"Headers\" tab below. The Authorization header holds the token, replacing the \"{{aWhereAccessToken}}\" part."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0239a05-d4e0-4104-a966-94a1c5ac1875"
            }
          ]
        }
      ]
    }
  ]
}