### <span style="color:#FFB400">POST</span> Authentication
#### `https://abby.my.salesforce.com/services/apexrest/Authenticate/API_Key/v1`
Endpoint that will validate the test the provided API Key for authenticity. API Keys are required to be sent for all other requests as an `x-api-key` header.

***

#### Body (json)
```json
{
    "api_key": "<insert API Key>"
}
```

### <span style="color:#0CBB52">GET</span> Chats
#### `https://abby.my.salesforce.com/services/apexrest/Chat/v1`
Returns the most recent Chats for your account

***

#### Request Headers

Headers | Values
------------ | -------------
x-api-key | /< your api key />

### <span style="color:#0CBB52">GET</span> Receptionist Messages
#### `https://abby.my.salesforce.com/services/apexrest/ReceptionistMessages/v1`
Returns the most recent Receptionist Messages for your account

***

#### Request Headers

Headers | Values
------------ | -------------
x-api-key | /< your api key />

### <span style="color:#0CBB52">GET</span> Call Records
#### `https://abby.my.salesforce.com/services/apexrest/CallRecord/v1`
Returns the most recent Call Records for your account

***

#### Request Headers

Headers | Values
------------ | -------------
x-api-key | /< your api key />