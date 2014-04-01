# ExampleUrl

    POST /fields/upsert

## Description

Insert or update a patient field, with the ability to automatically assign the patient field to all physicians.

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
	   "PatientField":{
		  "Name":"Field 2",
		  "DisplayName":null,
		  "DefaultValue":null,
		  "DataType":0,
		  "IsRequired":false,
		  "DisplayOrder":-1,
		  "Options":{

		  },
		  "Id":null
	   },
	   "AssignToAllPhysicians":false,
	   "ClientVersion":null
	}

**Response**

	{
	   "PatientFieldId":"533aeb4e3fd66728bcd5dbde",
	   "ErrorMessage":null,
	   "IsSuccessful":true,
	   "ServiceVersion":"2.2.6.9999"
	}
