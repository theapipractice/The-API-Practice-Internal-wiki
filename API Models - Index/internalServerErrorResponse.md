# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Internal Server Error Response |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Internal Server Error |  | internal_server_error | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |
| &gt; Internal Server Error Message |  | An unexpected error has occurred. | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |





```
{
  "error": "internal_server_error",
  "message": "An unexpected error has occurred."
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Internal Server Error Response",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "error": {
      "title": "Internal Server Error",
      "type": "string",
      "additionalProperties": true
    },
    "message": {
      "title": "Internal Server Error Message",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

