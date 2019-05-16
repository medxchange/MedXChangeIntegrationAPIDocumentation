# ExampleUrl

    POST /cases/current

## Description

Get the current case that is in progress. If no case is in progress, no case is returned.

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
	   "ClientVersion":null
	}

**Response**

	{
	   "CurrentCase":{
		  "FirstName":null,
		  "LastName":null,
		  "FullName":"Unknown",
		  "Index":1,
		  "PatientId":null,
		  "Sex":null,
		  "AccessionNumber":null,
		  "BirthDate":null,
		  "RefPhysician":null,
		  "SchPhysician":null,
		  "ProdId":null,
		  "ProdDescription":null,
		  "Modality":null,
		  "StudyDate":null,
		  "StudyDateSorted":"2014-04-01T15:12:56.079Z",
		  "Facility":null,
		  "Notes":null,
		  "IsOpen":true,
		  "PerformaingPhysicianId":null, /*not supported anymore, but left for legacy*/
		  "PerformingPhysician": null,
		  "AutoPrint":false,
		  "Archive":true,
		  "DateCreated":"2014-04-01T15:12:56.079Z",
		  "NumberOfVideos":0,
		  "NumberOfStills":0,
		  "UserDefined":{

		  },
		  "LastStartedOn":"2014-04-01T15:12:56.092Z",
		  "LastClosedOn":null,
		  "NumberOfMediaItems":0,
		  "DCIMGroup":"100",
		  "Id":"533ad7783fd667186c4d56a6"
	   },
	   "ServiceVersion":"3.4.2.9999"
	}
