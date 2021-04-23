# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Not Found Response |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Not Found Error |  | resource_not_found | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Not Found Message |  | Resource not found. | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "error": "resource_not_found",
  "message": "Resource not found."
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Not Found Response",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "error": {
      "title": "Not Found Error",
      "type": "string",
      "additionalProperties": true
    },
    "message": {
      "title": "Not Found Message",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

