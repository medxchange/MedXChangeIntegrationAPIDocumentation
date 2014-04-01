# ExampleUrl

    POST /physicians/get

## Description

Get a physician by id.

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
	   "PhysicianId":"533aeb923fd66728bcd5dc05",
	   "ClientVersion":null
	}

**Response**

	{
	   "Physician":{
		  "FullName":"test 1",
		  "DateCreated":"2014-04-01T16:38:41.956Z",
		  "SyncToGlobal":false,
		  "FieldAccessionNumberEnabled":false,
		  "FieldLastNameEnabled":true,
		  "FieldFirstNameEnabled":true,
		  "FieldPatientIdEnabled":true,
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
		  "DefaultPrintTemplate":"6Images_Portrait",
		  "AutoPrint":false,
		  "ImagesPerPage":0,
		  "SelectedPrinter":"Sony UP-DR80MD",
		  "NumberOfCopies":1,
		  "FourByThreeCrop":false,
		  "LogoEnabled":true,
		  "Logo":"logo.jpg",
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
		  "ImageFileType":"JPEG",
		  "VideoCompression":"4.2",
		  "VideoInput":"Vid_DVI",
		  "DVIColorShift":false,
		  "VideoFileType":"MP4",
		  "MuteAudio":false,
		  "MuteSystemAudio":false,
		  "EncryptionPassword":null,
		  "LiveStreamingPassword":"Password",
		  "LiveStreamingEnabled":false,
		  "LiveStreamingQuality":0,
		  "SegmentLengthSeconds":300,
		  "SegmentLengthEnabled":true,
		  "ForcePatientInfo":false,
		  "Bitrate":2,
		  "StorageFolderName":0,
		  "PreviewLayout":0,
		  "FluorescenceEnabled":false,
		  "FluorescenceIRVideoInput":"Vid_SVideo",
		  "FluorescenceWhiteLightVideoInput":"Vid_DVI",
		  "Id":"533aeb923fd66728bcd5dc05"
	   },
	   "ServiceVersion":"2.2.6.9999"
	}
