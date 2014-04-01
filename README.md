# MedXChange Integration (MI) API

MedXChange provides programmatic access to case data and media items. The API is refered to as MIAPI, which stands for **M**edXChange **I**ntegration**API**.

The API is a [REST API]. All request/response formats are [JSON].

## Checklist
* [See if the concepts used by the API are familiar to you] []
* Familiarize yourself with API functionality
* Read the MIAPI [API Terms of Use][]
* Hack away!

## SDK

* TBD

## Authentication

Before you can access any endpoint, you must first have a valid username and password setup on the device you are connecting with. Consult the manual for your MedXChange device to create a user that will be used for remote access to the device.

Every endpoint defined requires authentication, unless stated otherwise. A valid username and password must be provided to the [<code>AUTHENTICATE</code>] (endpoints/misc/authenticate.md) endpoint to retrieve a valid authentication token to use for each subsequent HTTP request. You must add the token to the header of each HTTP request being made to the device.

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


## Endpoints

### Miscellaneous

- **[<code>AUTHENTICATE</code>](endpoints/misc/authenticate.md)**
- **[<code>LIVE_STREAMING_STATUS</code>](endpoints/misc/livestreamingstatus.md)**
- **[<code>MODULE_STATUS</code>](endpoints/misc/modulestatus.md)**
- **[<code>VERSION</code>](endpoints/misc/version.md)**

### Cases

- **[<code>ALL_CASES</code>](endpoints/cases/allcases.md)**
- **[<code>REVIEW_CASES</code>](endpoints/cases/reviewcases.md)**
- **[<code>WORKLIST_CASES</code>](endpoints/cases/worklistcases.md)**
- **[<code>CURRENT_CASE</code>](endpoints/cases/currentcase.md)**
- **[<code>GET_CASE</code>](endpoints/cases/getcase.md)**
- **[<code>GET_CASE_FOR_EDIT</code>](endpoints/cases/getcaseforedit.md)**
- **[<code>INSERT_CASE</code>](endpoints/cases/insertcase.md)**
- **[<code>UPDATE_CASE</code>](endpoints/cases/updatecase.md)**
- **[<code>DELETE_CASE</code>](endpoints/cases/deletecase.md)**

### MediaItems

- **[<code>MEDIA_ITEMS_FOR_CASE</code>](endpoints/media_items/mediaitemsforcase.md)**
- **[<code>RECENT_MEDIA_ITEMS</code>](endpoints/media_items/recentmediaitems.md)**
- **[<code>DELETE_MEDIA_ITEM</code>](endpoints/media_items/deletemediaitem.md)**
- **[<code>MEDIA_ITEM_THUMBNAIL</code>](endpoints/media_items/mediaitemthumbnail.md)**
- **[<code>MEDIA_ITEM_FILE</code>](endpoints/media_items/mediaitemfile.md)**

### Physicains

- **[<code>GET_ALL_PHYSICIANS</code>](endpoints/physicians/getallphysicians.md)**
- **[<code>GET_PHYSICIAN</code>](endpoints/physicians/getphysician.md)**
- **[<code>DELETE_PHYSICIAN</code>](endpoints/physicians/deletephysician.md)**
- **[<code>INSERT_OR_UPDATE_PHYSICIAN</code>](endpoints/physicians/insertorupdatephysician.md)**
- **[<code>GET_ANNOTATIONS</code>](endpoints/physicians/getannotations.md)**

### Patient Fields

- **[<code>GET_PATIENT_FIELDS</code>](endpoints/patient_fields/getpatientfields.md)**
- **[<code>DELETE_PATIENT_FIELD</code>](endpoints/patient_fields/deletepatientfield.md)**
- **[<code>INSERT_OR_UPDATE_PATIENT_FIELD</code>](endpoints/patient_fields/insertorupdatepatientfield.md)**
- **[<code>ENABLE_DISABLE_PATIENT_FIELD</code>](endpoints/patient_fields/enabledisablepatientfield.md)**

## FAQ

* TBD

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
