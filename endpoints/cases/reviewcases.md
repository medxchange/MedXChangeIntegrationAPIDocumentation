# ExampleUrl

    POST /cases/review

## Description

Get a list of cases on the device that are filtered and sorted correctly to render a review section on the client. This request is similar to [<code>ALL_CASES</code>](../cases/allcases.md), but it returns only closed cases, sorted from last completed to oldest. Cases added to the worklist will not be returned, unless the case has been in progress at least once before.

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
			 "StudyDate":null,
			 "StudyDateSorted":"2014-04-01T16:17:40.003Z",
			 "Facility":null,
			 "Notes":null,
			 "IsOpen":false,
			 "PerformaingPhysicianId":null,
			 "AutoPrint":false,
			 "Archive":true,
			 "DateCreated":"2014-04-01T16:17:40.003Z",
			 "NumberOfVideos":0,
			 "NumberOfStills":0,
			 "UserDefined":{

			 },
			 "LastStartedOn":"2014-04-01T16:17:40.004Z",
			 "LastClosedOn":"2014-04-01T16:17:40.849Z",
			 "NumberOfMediaItems":0,
			 "DCIMGroup":"101",
			 "Id":"533ae6a43fd667139087295a"
		  },
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
			 "StudyDate":null,
			 "StudyDateSorted":"2014-04-01T16:17:39.498Z",
			 "Facility":null,
			 "Notes":null,
			 "IsOpen":false,
			 "PerformaingPhysicianId":null,
			 "AutoPrint":false,
			 "Archive":true,
			 "DateCreated":"2014-04-01T16:17:39.498Z",
			 "NumberOfVideos":0,
			 "NumberOfStills":0,
			 "UserDefined":{

			 },
			 "LastStartedOn":"2014-04-01T16:17:39.535Z",
			 "LastClosedOn":"2014-04-01T16:17:40.001Z",
			 "NumberOfMediaItems":0,
			 "DCIMGroup":"100",
			 "Id":"533ae6a33fd6671390872958"
		  }
	   ],
	   "PageIndex":0,
	   "PageSize":2147483647,
	   "TotalCount":2,
	   "TotalPages":1
	}
