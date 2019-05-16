# ExampleUrl

    POST /cases/worklist

## Description

Get a list of cases on the device that are scheduled to be performed to render a worklist section on the client. This request is similar to [<code>ALL_CASES</code>](../cases/allcases.md), but it returns only open cases, sorted by study date with upcoming cases appearing first.

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
	   "SearchText":null,
	   "PageIndex":0,
	   "PageSize":2147483647,
	   "ClientVersion":null
	}

**Response**

	{
	   "Cases":[
		  {
			 "FirstName":"Test 1",
			 "LastName":null,
			 "FullName":"Test 1",
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
			 "StudyDate":"2014-01-01T05:00:00Z",
			 "StudyDateSorted":"2014-01-01T05:00:00Z",
			 "Facility":null,
			 "Notes":null,
			 "IsOpen":true,
			 "PerformaingPhysicianId":null, /*not supported anymore, but left for legacy*/
		  	 "PerformingPhysician": null,
			 "AutoPrint":false,
			 "Archive":false,
			 "DateCreated":"2014-04-01T16:30:23.304Z",
			 "NumberOfVideos":0,
			 "NumberOfStills":0,
			 "UserDefined":{

			 },
			 "LastStartedOn":null,
			 "LastClosedOn":null,
			 "NumberOfMediaItems":0,
			 "DCIMGroup":"100",
			 "Id":"533ae99f3fd6672d18b50e06"
		  },
		  {
			 "FirstName":"Test 2",
			 "LastName":null,
			 "FullName":"Test 2",
			 "Index":2,
			 "PatientId":null,
			 "Sex":null,
			 "AccessionNumber":null,
			 "BirthDate":null,
			 "RefPhysician":null,
			 "SchPhysician":null,
			 "ProdId":null,
			 "ProdDescription":null,
			 "Modality":null,
			 "StudyDate":"2014-01-02T05:00:00Z",
			 "StudyDateSorted":"2014-01-02T05:00:00Z",
			 "Facility":null,
			 "Notes":null,
			 "IsOpen":true,
			 "PerformaingPhysicianId":null, /*not supported anymore, but left for legacy*/
		  	 "PerformingPhysician": null,
			 "AutoPrint":false,
			 "Archive":false,
			 "DateCreated":"2014-04-01T16:30:23.336Z",
			 "NumberOfVideos":0,
			 "NumberOfStills":0,
			 "UserDefined":{

			 },
			 "LastStartedOn":null,
			 "LastClosedOn":null,
			 "NumberOfMediaItems":0,
			 "DCIMGroup":"101",
			 "Id":"533ae99f3fd6672d18b50e07"
		  }
	   ],
	   "PageIndex":0,
	   "PageSize":2147483647,
	   "TotalCount":2,
	   "TotalPages":1
	}
