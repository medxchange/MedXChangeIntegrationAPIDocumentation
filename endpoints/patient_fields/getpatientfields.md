# ExampleUrl

    POST /fields/get

## Description

Get all the patient fields for the system or physician.

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
	   "PhysicianId":null,
	   "IncludeNative":false,
	   "ClientVersion":null
	}

**Response**

	{
	   "PatientFields":[
		  {
			 "Name":"Field 1",
			 "DisplayName":null,
			 "DefaultValue":null,
			 "DataType":0,
			 "IsRequired":false,
			 "DisplayOrder":0,
			 "Options":{

			 },
			 "Id":"533aeb4e3fd66728bcd5dbdd"
		  },
		  {
			 "Name":"Field 2",
			 "DisplayName":null,
			 "DefaultValue":null,
			 "DataType":0,
			 "IsRequired":false,
			 "DisplayOrder":0,
			 "Options":{

			 },
			 "Id":"533aeb4e3fd66728bcd5dbde"
		  }
	   ],
	   "ServiceVersion":"2.2.6.9999"
	}
