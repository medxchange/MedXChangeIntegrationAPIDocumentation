# ExampleUrl

    POST /cases/get

## Description

Get a specific case by id.

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
	   "CaseId":"533ad7a03fd667186c4d56be",
	   "ClientVersion":null
	}

**Response**

	{
	   "Case":{
		  "FirstName":"first",
		  "LastName":"last",
		  "FullName":"last, first",
		  "Index":1,
		  "PatientId":"pid",
		  "Sex":"Male",
		  "AccessionNumber":"an",
		  "BirthDate":"2011-12-12T05:00:00Z",
		  "RefPhysician":"ref",
		  "SchPhysician":"sch",
		  "ProdId":"prodid",
		  "ProdDescription":"proddesc",
		  "Modality":"mod",
		  "StudyDate":"2012-11-11T05:00:00Z",
		  "StudyDateSorted":"2012-11-11T05:00:00Z",
		  "Facility":"f",
		  "Notes":"notes",
		  "IsOpen":true,
		  "PerformaingPhysicianId":null,
		  "AutoPrint":true,
		  "Archive":true,
		  "DateCreated":"2014-04-01T15:13:36.127Z",
		  "NumberOfVideos":0,
		  "NumberOfStills":0,
		  "UserDefined":{

		  },
		  "LastStartedOn":null,
		  "LastClosedOn":null,
		  "NumberOfMediaItems":0,
		  "DCIMGroup":"100",
		  "Id":"533ad7a03fd667186c4d56be"
	   },
	   "ServiceVersion":"3.4.2.9999"
	}
