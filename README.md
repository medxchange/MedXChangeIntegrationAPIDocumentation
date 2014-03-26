# MedXChange Integration (MI) API

MedXChange provides programmatic access to case data and media items. The API is refered to as MIAPI, which stands for MedXChangeIntegrationAPI.

The API is a [REST API]. All request/response formats are [JSON].

## Checklist
* [See if the concepts used by the API are familiar to you] []
* Familiarize yourself with API functionality
* Read the MIAPI [API Terms of Use][]
* Hack away

## Authentication

Before you can access any endpoint, you must first have a valid username and password setup on the device you are connecting with. Consult the manual for your MedXChange device to create a user that will be used for remote access to the device.

Every endpoint defined requires authentication, unless stated otherwise. A valid username and password must be provided to the [AUTHENTICATE] (endpoints/misc/authenticate.md) endpoint to retrieve a valid authentication token to use for each subsequent HTTP request. You must add the token to the header of each HTTP request being made to the device.

```
token: {your authentication token here}
```

If your authentication token is invalid, you will receive a `HTTP 401` response with the following JSON response.

``` json
{
  "TokenStatus" : 2,
  "ErrorMessage" : "Your authorization token is invalid."
}
```

## SDK

* TBD

## Endpoints

## Authentication

* TBD

## FAQ

### What do I need to know before I start using the API?

Got rust on your skills? No worries. Here are the docs you might need to get started:

- HTTPS protocol
- [REST software pattern][]
- Data serialization with [JSON][] (or see a [quick tutorial][])

[See if the concepts used by the API are familiar to you]: https://tbd.com/#what-do-i-need-to-know-before-i-start-using-the-api
[API Terms of Use]: basic/terms_of_use.md
[JSON]: http://json.org
[REST software pattern]: http://en.wikipedia.org/wiki/Representational_State_Transfer
[REST API]: http://en.wikipedia.org/wiki/Representational_State_Transfer "RESTful"
