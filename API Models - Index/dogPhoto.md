# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Dog Photo |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Dog Photo Id |  | 1 | No | No | No | No |  |Data Type : number<br> Mininum : 1<br> Exclusive Minimum : No<br> Maximum : 90<br> Exclusive Maximum : No<br> Multiple Of :  - <br> Allow Null : false<br>  |
| &gt; Dog Photo Name |  | aaaa | No | No | No | No |  |Data Type : string<br> Min. length : 1<br> Max. length : 50<br> Regex :  - <br> Allow Null : false<br> Faker : address.streetName<br>  |
| &gt; Comments |  |  -  | No | No | No | No |  |Data Type : array<br>  |
| &gt; Comment |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Comment Id |  | 48d68cdc-4860-46fa-9c9b-497115961eb3 | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Comment Message |  | message | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Likes |  |  -  | No | No | No | No |  |Data Type : array<br>  |
| &gt; User name |  | dy | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |





```
{
  "dogPhotoId": 1.0,
  "dogPhotoName": "aaaa",
  "comments": [
    {
      "commentId": "48d68cdc-4860-46fa-9c9b-497115961eb3",
      "commentMessage": "message"
    }
  ],
  "likes": [
    "dy"
  ]
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Dog Photo",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "dogPhotoId": {
      "title": "Dog Photo Id",
      "type": "number",
      "additionalProperties": true,
      "minimum": 1.0,
      "maximum": 90.0
    },
    "dogPhotoName": {
      "title": "Dog Photo Name",
      "type": "string",
      "additionalProperties": true,
      "minLength": 1,
      "maxLength": 50
    },
    "comments": {
      "title": "Comments",
      "type": "array",
      "additionalProperties": true,
      "items": {
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
    },
    "likes": {
      "title": "Likes",
      "type": "array",
      "additionalProperties": true,
      "items": {
        "title": "User name",
        "type": "string",
        "additionalProperties": true
      }
    }
  }
}
```

