# ExampleUrl

    POST /cases/update

## Description

Update a case by id.

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
	   "CaseId":"533ae8793fd66712e0765943",
	   "PerformingPhysician":null,
	   "Values":{
		  "FirstName":"modified"
	   },
	   "ClientVersion":null
	}

**Response**

	{
	   "CaseId":"533ae8793fd66712e0765943",
	   "ErrorMessage":null,
	   "IsSuccessful":true,
	   "ServiceVersion":"2.2.6.9999"
	}
