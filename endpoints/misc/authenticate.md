# ExampleUrl

    POST /authenticate

## Description

Authenticate against the device. After authentication, you will receive a valid authentication token that can be used for subsequence requests. The username/password must be configuired on the device. Consult the devices manual for instructions on setting up users.

This request doesn't require as an authentication token, because it is used to aquire one.

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
	   "Username":"username",
	   "Password":"password",
	   "ClientVersion":null
	}

**Response**

	{
	   "WasAuthenticationRequired":true,
	   "AuthenticationToken":null,
	   "ErrorMessage":"The username or password is incorrect.",
	   "IsSuccessful":false,
	   "ServiceVersion":"2.2.6.9999"
	}
