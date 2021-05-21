# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Dog |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Dog Id |  | 1 | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Dog Name |  | kiki | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br> Allow Null : false<br> Faker : name.firstName<br>  |
| &gt; dog photos |  |  -  | No | No | No | No |  |Data Type : array<br>  |
| &gt; test |  | aa | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Dog Addresses |  |  -  | No | No | No | No |  |Data Type : array<br>  |





```
{
  "dogId": 1,
  "dogName": "kiki",
  "dogPhotos": [
    "aa"
  ],
  "dogAddresses": []
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Dog",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "dogId": {
      "title": "Dog Id",
      "type": "integer",
      "additionalProperties": true
    },
    "dogName": {
      "title": "Dog Name",
      "type": "string",
      "additionalProperties": true
    },
    "dogPhotos": {
      "title": "dog photos",
      "type": "array",
      "additionalProperties": true,
      "items": {
        "title": "test",
        "type": "string",
        "additionalProperties": true
      }
    },
    "dogAddresses": {
      "title": "Dog Addresses",
      "type": "array",
      "additionalProperties": true
    }
  }
}
```

