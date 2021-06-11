# Idempotent Requests

An idempotent request is one which can safely be made multiple times, but will only be processed once. Some of our endpoints support an `Idempotency-Key` header, which is a value supplied by you to uniquely identify that request. If the same request is made to the same endpoint with the same `Idempotency-Key` header value, it will not be processed a second time.

The value of your `Idempotency-Key` header should be a string with a length between 10 and 100 characters inclusive.

When sending an `Idempotency-Key` header with a request, the usual API contract for that endpoint applies, with the following additions:

| Status | Meaning     | Description                                                                                             |
|--------|-------------|---------------------------------------------------------------------------------------------------------|
| 400    | [Bad Request](https://tools.ietf.org/html/rfc7231#section-6.5.1) | Either the Idempotency-Key header is required and is missing, or it has an invalid length               |
| 409    | [Conflict](https://tools.ietf.org/html/rfc7231#section-6.5.8)    | A request with the same Idempotency-Key header has already been received, but it had different contents |

Refer to the error message in the response for further details.