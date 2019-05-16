# ExampleUrl

    POST /fields/enabledisable

## Description

Enable or disable a patient field for the user. All patient fields are enabled for the system by default.

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
	   "PhysicianId":"", /*not supported anymore, but left for legacy*/
	   "PatientFieldId":"533aeb243fd66728bcd5dbc8",
	   "Action":0,
	   "ClientVersion":null
	}

**Response**

	{
	   "ErrorMessage":null,
	   "IsSuccessful":true,
	   "ServiceVersion":"2.2.6.9999"
	}