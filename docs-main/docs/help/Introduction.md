---
tags: [Help]
---

# Introduction

Get to market faster using our financial services APIs.

---

## Environments

We have a separate staging environment where you can try out our APIs. All of the code snippets below will use the staging environment. You can find the details for both our staging and production environment below:

### Sandbox
`https://auth.sandbox.wealthkernel.io`

`https://api.sandbox.wealthkernel.io`

### Production

<!-- theme: info -->
> Please contact your Customer Success Manager for Production URLs and tokens

---

## Versioning

To set the API version on a request, set the `Accept-Version` to the version you want to use. When not supplied, it will default to your default API version.

### Version Changes

When backwards incompatible changes are made to the API we will release a new version of the API which will be dated (e.g. `2019-07-16`).

### Breaking changes
The following changes would be considered breaking:

- Changing the location of a resource
- Removing a property from a response
- Changing the status code of a response
- Removal of query parameters, including optional

Changes that would not be considered breaking:
- Adding a new resource or endpoint
- Adding a new property to a response
- Adding new optional parameters to requests
- Adding new methods to an existing endpoint
- Changing the order of properties
- Removal of undocumented properties

## Dates and times
Date and date-time data types are in UTC and are ISO8601 formatted.

### Date
`2019-10-08`

### Date-time
`2019-10-08T13:55:16.4237925Z`