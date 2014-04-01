# ExampleUrl

    POST /cases/delete

## Description

Delete a case from the device by id.

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
	   "CaseId":"533ad7cb3fd667186c4d56d4",
	   "ClientVersion":null
	}

**Response**

	{
	   "WasCaseDeleted":false,
	   "ErrorMessage":"You cannot delete a case that is currently in progress.",
	   "IsSuccessful":false,
	   "ServiceVersion":"3.4.2.9999"
	}
