# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Dog A |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Dog Photos |  |  -  | No | No | No | No |  |Data Type : array<br>  |
| &gt; test name |  | aaa | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "dogPhotos": [
    "aaa"
  ]
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Dog A",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "dogPhotos": {
      "title": "Dog Photos",
      "type": "array",
      "additionalProperties": true,
      "items": {
        "title": "test name",
        "type": "string",
        "additionalProperties": true
      }
    }
  }
}
```

