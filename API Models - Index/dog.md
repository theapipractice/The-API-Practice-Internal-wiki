# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Dog |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Dog Id |  | 1 | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Dog Name |  | kiki | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br> Allow Null : false<br> Faker : name.firstName<br>  |
| &gt; Dog Address |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Dog Address Id |  | 1 | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Dog Address Name |  | ho chi minh | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Dog Photos |  |  -  | No | No | No | No |  |Data Type : array<br>  |
| &gt; Dog Photo |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Dog Photo Id |  | 1 | No | No | No | No |  |Data Type : number<br> Mininum : 1<br> Exclusive Minimum : No<br> Maximum : 90<br> Exclusive Maximum : No<br> Multiple Of :  - <br> Allow Null : false<br>  |
| &gt; Dog Photo Name |  | aaaa | No | No | No | No |  |Data Type : string<br> Min. length : 1<br> Max. length : 50<br> Regex :  - <br> Allow Null : false<br> Faker : address.streetName<br>  |





```
{
  "dogId": 1,
  "dogName": "kiki",
  "dogAddress": {
    "dogAddressId": 1,
    "dogAddressName": "ho chi minh"
  },
  "dogPhotos": [
    {
      "dogPhotoId": 1.0,
      "dogPhotoName": "aaaa"
    }
  ]
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
    "dogAddress": {
      "title": "Dog Address",
      "type": "object",
      "additionalProperties": true,
      "properties": {
        "dogAddressId": {
          "title": "Dog Address Id",
          "type": "integer",
          "additionalProperties": true
        },
        "dogAddressName": {
          "title": "Dog Address Name",
          "type": "string",
          "additionalProperties": true
        }
      }
    },
    "dogPhotos": {
      "title": "Dog Photos",
      "type": "array",
      "additionalProperties": true,
      "items": {
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
          }
        }
      }
    }
  }
}
```

