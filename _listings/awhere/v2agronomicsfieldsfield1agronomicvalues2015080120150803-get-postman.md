{
  "info": {
    "name": "aWhere Agronomic Values & Accumulations",
    "_postman_id": "659d4569-2f7c-4212-a8ee-8850a054b69f",
    "description": "####Request\nThis API call gets calculated agronomics and accumulations at a field location. \n\nThe URL used here will get the values for a certain range of days. This is a very flexible API and so you're encouraged to review the [Agronomics Documentation](http://developer.awhere.com/api/reference/agronomics/values).\n\n_Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the security Access Token that is retrieved with the \"Get a Token\" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the \"Headers\" tab below. The Authorization header holds the token, replacing the \"{{aWhereAccessToken}}\" part.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Agriculture",
      "item": [
        {
          "id": "a64dc968-4385-489e-8633-3c0ceb80d076",
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
              "id": "c152eebb-ef51-4065-822c-af2b39c32304"
            }
          ]
        }
      ]
    }
  ]
}