# ExampleUrl

    POST /cases/insert

## Description

Insert a case with patient data. The fields that should be passed to this endpoint should be gathered using the  [<code>GET_PATIENT_FIELDS</code>](../patient_fields/getpatientfields.md) endpoint.

## Request Parameters

TBd

***

## Response Parameters

TBD

***

## Example
**Request**

	{
	   "PerformingPhysician":null,
	   "Values":{
		  "AccessionNumber":"an",
		  "Archive":true,
		  "AutoPrint":true,
		  "BirthDate":"2011-12-12T00:00:00",
		  "Facility":"f",
		  "FirstName":"first",
		  "LastName":"last",
		  "Modality":"mod",
		  "Notes":"notes",
		  "PatientId":"pid",
		  "ProdDescription":"proddesc",
		  "ProdId":"prodid",
		  "RefPhysician":"ref",
		  "SchPhysician":"sch",
		  "Sex":"Male",
		  "StudyDate":"2012-11-11T00:00:00"
	   },
	   "ClientVersion":null
	}

**Response**

	{
	   "CaseId":null,
	   "ErrorMessage":"The fields FirstName, LastName, PatientId are required or invalid.",
	   "IsSuccessful":false,
	   "ServiceVersion":"3.4.2.9999"
	}