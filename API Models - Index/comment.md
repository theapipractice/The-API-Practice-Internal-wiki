# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Comment |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Comment Id |  | 48d68cdc-4860-46fa-9c9b-497115961eb3 | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Comment Message |  | message | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "commentId": "48d68cdc-4860-46fa-9c9b-497115961eb3",
  "commentMessage": "message"
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Comment",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "commentId": {
      "title": "Comment Id",
      "type": "string",
      "additionalProperties": true
    },
    "commentMessage": {
      "title": "Comment Message",
      "type": "string",
      "additionalProperties": true
    }
  }
}
```

