# ExampleUrl

    POST /physicians/delete

## Description

Delete a physician by id. All cases assigned to the given physician will be re-assigned to have no performing physician.

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
	   "PhysicianId":"533aeb203fd66728bcd5dbc7",
	   "ClientVersion":null
	}

**Response**

	{
	   "ErrorMessage":null,
	   "IsSuccessful":true,
	   "ServiceVersion":"2.2.6.9999"
	}
