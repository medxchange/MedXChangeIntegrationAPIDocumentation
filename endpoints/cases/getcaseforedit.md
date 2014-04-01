# ExampleUrl

    POST /cases/getforedit

## Description

Get a list of valid fields with values populated using a case id. This is used to render a case edit page with case data. If you need to render a case insert page, retrieve the patient fields for the system/physician using [<code>GET_PATIENT_FIELDS</code>](../patient_fields/getpatientfields.md)

***

## Request Parameters

TBD

***

## Response Parameters

TBD

***

## Example
**Request**

	{
	   "CaseId":"533ad7703fd667186c4d56a5",
	   "ClientVersion":null
	}

**Response**

	{
	   "PerformingPhysicianId":null,
	   "Values":[
		  {
			 "Value":"First 1",
			 "Name":"FirstName",
			 "DisplayName":"FirstName",
			 "DefaultValue":null,
			 "DataType":0,
			 "IsRequired":false,
			 "DisplayOrder":-1,
			 "Options":{

			 },
			 "Id":null
		  },
		  {
			 "Value":"Last 1",
			 "Name":"LastName",
			 "DisplayName":"LastName",
			 "DefaultValue":null,
			 "DataType":0,
			 "IsRequired":false,
			 "DisplayOrder":-1,
			 "Options":{

			 },
			 "Id":null
		  },
		  {
			 "Value":"Patient id",
			 "Name":"PatientId",
			 "DisplayName":"PatientId",
			 "DefaultValue":null,
			 "DataType":0,
			 "IsRequired":false,
			 "DisplayOrder":-1,
			 "Options":{

			 },
			 "Id":null
		  },
		  {
			 "Value":false,
			 "Name":"AutoPrint",
			 "DisplayName":"AutoPrint",
			 "DefaultValue":"False",
			 "DataType":4,
			 "IsRequired":false,
			 "DisplayOrder":-1,
			 "Options":{

			 },
			 "Id":null
		  },
		  {
			 "Value":false,
			 "Name":"Archive",
			 "DisplayName":"Archive",
			 "DefaultValue":"False",
			 "DataType":4,
			 "IsRequired":false,
			 "DisplayOrder":-1,
			 "Options":{

			 },
			 "Id":null
		  }
	   ],
	   "CaseId":null,
	   "ErrorMessage":null,
	   "IsSuccessful":true,
	   "ServiceVersion":"3.4.2.9999"
	}
