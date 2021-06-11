# Authentication

All API request require an authorization header with a bearer token. An access token can be retrieved from our authorization server using [OAuth2 client credentials flow](https://tools.ietf.org/html/rfc6749#section-4.4).

If you would like to use our API please register your interest at [wealthkernel.com/enquiries](https://www.wealthkernel.com/enquiries) and we will issue you a `client_id` and `client_secret`.

sdasdasd

```json http
{
  "method": "POST",
  "url": "https://auth.sandbox.wealthkernel.io/connect/token",
  "headers":{
    "Content-Type": "multipart/form-data"
  }
  "body": {
    "contents": [
       {"something": "somethinelse" }
    ]
  }
}
```

### Request

```yaml json_schema
title: Auth Request
type: object
properties:
  grant_type:
    type: string
    enum: ['client_credentials']
    description: Must be "client_credentials".
  client_id:
    type: string
    description: Your unique client identifier.
  client_secret:
    type: string
    description: Your client secret.
  scope:
    type: string
    description: Must be wk.gateway.
```

### Response

```yaml json_schema
title: Auth Response
type: object
properties:
  access_token:
    type: string
    description: Access token to be used in authorization header.
  expires_in:
    type: number
    description: Time in seconds token expires in.
  token_type: 
    type: string
    description: Type of token.
```