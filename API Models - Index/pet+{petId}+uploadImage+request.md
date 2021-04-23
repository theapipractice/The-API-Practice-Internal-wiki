# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  pet {petId} uploadImage request |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; additionalMetadata |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; file |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "additionalMetadata": "",
  "file": ""
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "pet {petId} uploadImage request",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "additionalMetadata": {
      "title": "additionalMetadata",
      "type": "string",
      "additionalProperties": true
    },
    "file": {
      "title": "file",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

