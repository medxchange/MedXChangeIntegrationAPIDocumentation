# ExampleUrl

    POST /media/forcase

## Description

Get a list of media items for a case.

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
	   "ForCaseId":"533aeb4a3fd66728bcd5dbda",
	   "MediaType":null,
	   "ClientVersion":null
	}

**Response**

	{
	   "MediaItems":[
		  {
			 "MediaType":1,
			 "CaseId":"533aeb4a3fd66728bcd5dbda",
			 "FilePath":"mp4",
			 "IsFLLoop":false,
			 "AnnotationText":null,
			 "DateCreated":"2014-04-01T16:37:30.29Z",
			 "Index":1,
			 "ImagePath":"mp4",
			 "ConvertedFilePath":"mp4",
			 "Id":"533aeb4a3fd66728bcd5dbdb"
		  },
		  {
			 "MediaType":0,
			 "CaseId":"533aeb4a3fd66728bcd5dbda",
			 "FilePath":"png",
			 "IsFLLoop":false,
			 "AnnotationText":null,
			 "DateCreated":"2014-04-01T16:37:30.292Z",
			 "Index":1,
			 "ImagePath":"png",
			 "ConvertedFilePath":"png",
			 "Id":"533aeb4a3fd66728bcd5dbdc"
		  }
	   ],
	   "ServiceVersion":"2.2.6.9999"
	}
