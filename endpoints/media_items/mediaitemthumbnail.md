# ExampleUrl

    GET /media/thumbnail/{id}

## Description

Get a media item thumbnail. This file is always a scalled-down jpeg.

***

## Request Parameters

None

***

## Response Parameters

None

***

## Response Headers

- **MediaExtension** - The file extension of this media item. When downloading the file, it should be saved to the file system using this extension. Valid extensions include ".mp4", ".jpeg", ".mov", etc.
- **MediaItemLength** - The length of the file in bytes. This is provided so that a seperate HTTP HEAD request isn't required first to get the target file size to render a progress bar correctly.

***

## Example

None
