# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Unauthorised Response |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Unauthorised Error |  | unauthorised | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Unauthorised Message |  | Unauthorised. Please check your credentials. | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "error": "unauthorised",
  "message": "Unauthorised. Please check your credentials."
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Unauthorised Response",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "error": {
      "title": "Unauthorised Error",
      "type": "string",
      "additionalProperties": true
    },
    "message": {
      "title": "Unauthorised Message",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

