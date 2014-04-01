# ExampleUrl

    POST /physicians/upsert

## Description

Insert a new physician or update an existing physician.

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
	   "Physician":{
		  "FullName":"test 2",
		  "DateCreated":"2014-04-01T16:37:59.1509952Z",
		  "SyncToGlobal":false,
		  "FieldAccessionNumberEnabled":false,
		  "FieldLastNameEnabled":false,
		  "FieldFirstNameEnabled":false,
		  "FieldPatientIdEnabled":false,
		  "FieldSexEnabled":false,
		  "FieldBirthdateEnabled":false,
		  "FieldRefPhysiciansEnabled":false,
		  "FieldSchPhysiciansEnabled":false,
		  "FieldProdIdEnabled":false,
		  "FieldProdDescEnabled":false,
		  "FieldModalityEnabled":false,
		  "FieldStudyDateEnabled":false,
		  "FieldFacilityEnabled":false,
		  "FieldDefaultFacilitySetting":null,
		  "FieldNotesEnabled":false,
		  "DefaultPrintTemplate":null,
		  "AutoPrint":false,
		  "ImagesPerPage":0,
		  "SelectedPrinter":null,
		  "NumberOfCopies":1,
		  "FourByThreeCrop":false,
		  "LogoEnabled":true,
		  "Logo":null,
		  "Header":null,
		  "Footer1":null,
		  "Footer2":null,
		  "Footer3":null,
		  "Footer4":null,
		  "Footer5":null,
		  "Footer6":null,
		  "Gamma":null,
		  "Brightness":null,
		  "Saturation":null,
		  "Sharpen":null,
		  "Contrast":null,
		  "Hue":null,
		  "ArchivingEnabled":false,
		  "AutoArchiving":true,
		  "AutoArchivePriority":0,
		  "ArchivingLocation":null,
		  "RemoteArchivingLocation":null,
		  "ImageFileType":null,
		  "VideoCompression":null,
		  "VideoInput":null,
		  "DVIColorShift":false,
		  "VideoFileType":null,
		  "MuteAudio":false,
		  "MuteSystemAudio":false,
		  "EncryptionPassword":null,
		  "LiveStreamingPassword":"Password",
		  "LiveStreamingEnabled":false,
		  "LiveStreamingQuality":0,
		  "SegmentLengthSeconds":0,
		  "SegmentLengthEnabled":true,
		  "ForcePatientInfo":false,
		  "Bitrate":0,
		  "StorageFolderName":0,
		  "PreviewLayout":0,
		  "FluorescenceEnabled":false,
		  "FluorescenceIRVideoInput":"Vid_SVideo",
		  "FluorescenceWhiteLightVideoInput":"Vid_DVI",
		  "Id":null
	   },
	   "ClientVersion":null
	}

**Response**

	{
	   "PhysicianId":"533aeb673fd66728bcd5dbee",
	   "ErrorMessage":null,
	   "IsSuccessful":true,
	   "ServiceVersion":"2.2.6.9999"
	}
