# ExampleUrl

    POST /physicians/annotations

## Description

Get all the available annotations. If a physician id is given, then private annotations for the physician will also be returned.

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
	   "ForPhysicianId":null,
	   "FilterText":"test 12",
	   "ClientVersion":null
	}

**Response**

	{
	   "Annotations":[
		  {
			 "PhysicianId":"533aeb283fd66728bcd5dbcd",
			 "Text":"test 12",
			 "IsShared":true,
			 "Id":"533aeb283fd66728bcd5dbd0"
		  },
		  {
			 "PhysicianId":"533aeb283fd66728bcd5dbce",
			 "Text":"test 123",
			 "IsShared":true,
			 "Id":"533aeb283fd66728bcd5dbd1"
		  }
	   ],
	   "ServiceVersion":"2.2.6.9999"
	}
