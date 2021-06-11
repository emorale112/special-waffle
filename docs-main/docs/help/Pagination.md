# Pagination

List requests on many of the resources are paginated. To page through results use the following query parameters:

`GET https://api.staging.wealthkernel.io/parties?limit=20&after=a6f0`

| Parameter | Type    | Description                                                                             |
|-----------|---------|-----------------------------------------------------------------------------------------|
| limit     | integer | The maximum number of resources to return. If not supplied the default 20 will be used. |
| after     | string  | A token for the position to offset from. See Pagination-Last.                           |

## Pagination-Last Header

The header `Pagination-Last` will be set in the response if there are further results and should be used as the next request's `after` value.