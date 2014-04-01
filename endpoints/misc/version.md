# ExampleUrl

    POST /version

## Description

Used to ping a device for availability and get the running services/versions on the device. 

This method should be called before communicating with the device in any other way to verify version numbers. Client implementations should manage situations where older clients don't support communicating with newer endpoints that may have different endpoints and a different JSON schema.

If this method doesn't respond with a valid response, you can assume that the device is unavailable.

***

## Request Parameters

***

## Response Parameters

***

## Errors

***

## Example
**Request**

	{
	   "ClientVersion":null
	}

**Response**

	{
	   "ServiceInfo":{
		  "Endpoints":[
			 {
				"IPAddress":"192.168.1.1",
				"Port":4949,
				"Name":"core",
				"DisplayName":"Core",
				"Version":"1.1.1.0"
			 },
			 {
				"IPAddress":"192.168.1.1",
				"Port":4949,
				"Name":"evo",
				"DisplayName":"EvolutionHD",
				"Version":"2.4.5.9999"
			 }
		  ],
		  "IPAddress":"192.168.1.1",
		  "MacAddress":"BD8551F0322A"
	   },
	   "ServiceVersion":"2.2.6.9999"
	}
