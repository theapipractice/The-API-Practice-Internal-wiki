# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  pet {petId} request |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Category name |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; status |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br> Enum : placed, approved, delivered<br>  |





```
{
  "name": "",
  "status": "placed"
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "pet {petId} request",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "name": {
      "title": "Category name",
      "type": "string",
      "additionalProperties": true
    },
    "status": {
      "title": "status",
      "type": "string",
      "additionalProperties": true,
      "enum": [
        "placed",
        "approved",
        "delivered"
      ]
    }
  }
}
```

