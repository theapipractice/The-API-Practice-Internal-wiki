# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Bad Request Response |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Bad Request Error |  | bad_request | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Bad Request Message |  | Bad Request | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "error": "bad_request",
  "message": "Bad Request"
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Bad Request Response",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "error": {
      "title": "Bad Request Error",
      "type": "string",
      "additionalProperties": true
    },
    "message": {
      "title": "Bad Request Message",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

