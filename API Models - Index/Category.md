# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Category |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Order id |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Category name |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "id": 0,
  "name": ""
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Category",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "id": {
      "title": "Order id",
      "type": "integer",
      "additionalProperties": true
    },
    "name": {
      "title": "Category name",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

