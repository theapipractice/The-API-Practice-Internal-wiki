# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  User |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Order id |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; username |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; firstName |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; lastName |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; email |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; password |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; phone |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; userStatus |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "id": 0,
  "username": "",
  "firstName": "",
  "lastName": "",
  "email": "",
  "password": "",
  "phone": "",
  "userStatus": 0
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "User",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "id": {
      "title": "Order id",
      "type": "integer",
      "additionalProperties": true
    },
    "username": {
      "title": "username",
      "type": "string",
      "additionalProperties": true
    },
    "firstName": {
      "title": "firstName",
      "type": "string",
      "additionalProperties": true
    },
    "lastName": {
      "title": "lastName",
      "type": "string",
      "additionalProperties": true
    },
    "email": {
      "title": "email",
      "type": "string",
      "additionalProperties": true
    },
    "password": {
      "title": "password",
      "type": "string",
      "additionalProperties": true
    },
    "phone": {
      "title": "phone",
      "type": "string",
      "additionalProperties": true
    },
    "userStatus": {
      "title": "userStatus",
      "type": "integer",
      "additionalProperties": true
    }
  }
}
```

