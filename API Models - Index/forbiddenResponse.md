# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Forbidden Response |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Forbidden Error |  | forbidden | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Forbidden Message |  | Forbidden. You do not have permission to perform this action. | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "error": "forbidden",
  "message": "Forbidden. You do not have permission to perform this action."
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Forbidden Response",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "error": {
      "title": "Forbidden Error",
      "type": "string",
      "additionalProperties": true
    },
    "message": {
      "title": "Forbidden Message",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

