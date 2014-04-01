# ExampleUrl

    POST /media/recent

## Description

Get all the recent media items that were taken on the device.

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
	   "MinutesAgo":5,
	   "MaximumNumber":2147483647,
	   "MediaType":null,
	   "ClientVersion":null
	}

**Response**

	{
	   "MediaItems":[
		  {
			 "MediaType":0,
			 "CaseId":"533aeb513fd66728bcd5dbdf",
			 "FilePath":"C:\\Cases\\MX140401_14015455\\Stills\\tmpDB58.jpg",
			 "IsFLLoop":false,
			 "AnnotationText":null,
			 "DateCreated":"2014-04-01T16:35:37.944Z",
			 "Index":1,
			 "ImagePath":"C:\\Cases\\MX140401_14015455\\Stills\\tmpDB58.jpg",
			 "ConvertedFilePath":"C:\\Cases\\MX140401_14015455\\Stills\\tmpDB58.jpg",
			 "Id":"533aeb513fd66728bcd5dbe2"
		  },
		  {
			 "MediaType":0,
			 "CaseId":"533aeb513fd66728bcd5dbe0",
			 "FilePath":"C:\\Cases\\MX140401_14015456\\Stills\\tmpDB59.jpg",
			 "IsFLLoop":false,
			 "AnnotationText":null,
			 "DateCreated":"2014-04-01T16:33:37.944Z",
			 "Index":1,
			 "ImagePath":"C:\\Cases\\MX140401_14015456\\Stills\\tmpDB59.jpg",
			 "ConvertedFilePath":"C:\\Cases\\MX140401_14015456\\Stills\\tmpDB59.jpg",
			 "Id":"533aeb513fd66728bcd5dbe3"
		  }
	   ],
	   "Cases":[
		  {
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
			 "StudyDateSorted":"2014-04-01T16:37:37.944Z",
			 "Facility":null,
			 "Notes":null,
			 "IsOpen":true,
			 "PerformaingPhysicianId":null,
			 "AutoPrint":false,
			 "Archive":false,
			 "DateCreated":"2014-04-01T16:37:37.944Z",
			 "NumberOfVideos":0,
			 "NumberOfStills":1,
			 "UserDefined":{

			 },
			 "LastStartedOn":null,
			 "LastClosedOn":null,
			 "NumberOfMediaItems":1,
			 "DCIMGroup":"100",
			 "Id":"533aeb513fd66728bcd5dbdf"
		  },
		  {
			 "FirstName":null,
			 "LastName":null,
			 "FullName":"Unknown",
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
			 "StudyDateSorted":"2014-04-01T16:37:37.953Z",
			 "Facility":null,
			 "Notes":null,
			 "IsOpen":true,
			 "PerformaingPhysicianId":null,
			 "AutoPrint":false,
			 "Archive":false,
			 "DateCreated":"2014-04-01T16:37:37.953Z",
			 "NumberOfVideos":0,
			 "NumberOfStills":1,
			 "UserDefined":{

			 },
			 "LastStartedOn":null,
			 "LastClosedOn":null,
			 "NumberOfMediaItems":1,
			 "DCIMGroup":"101",
			 "Id":"533aeb513fd66728bcd5dbe0"
		  }
	   ]
	}
