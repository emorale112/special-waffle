# Actions

Some resources have actions that can be applied to them, which have the following pattern.

`POST https://api.staging.wealthkernel.io/{resource}/{resource-id}/actions/{action}`

For example, if you were to cancel an order you would do the following:

`POST https://api.staging.wealthkernel.io/orders/ord-32q2dek3j263q4/actions/cancel`

Here are some more updates to a file to test it. 



Input Parameter| Required/Optional | Format | Remark
---------|----------|---------|---------
 A1 | B1 | C1 |
 A2 | B2 | C2 |
 A3 | B3 | C3 |

Here are some more of my edits that I want to check and facilitate. 

 Input Parameter	Required/Optional	Format	Remark
Client_ID	Required	########-####-####-####-############ where # is alphanumeric	Unique identifier for a client provided by Debitsuccess.
Client_Secret	Required	64 bit	Client secret key provided by Debitsuccess.
Grant_Type	Required	stringclient_credentials	Denotes the flow you are using. Always use client_credentials
scope	Optional	Space-separated string	The name of the API that access token will be generated for.If the scope is not provided by Debitsuccess, you can ignore this field in the request body. Also if the scope is not provided the token will contain all available scopes for this client_id.
