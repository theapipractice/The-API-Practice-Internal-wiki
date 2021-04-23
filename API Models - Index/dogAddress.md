# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Dog Address |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Dog Address Id |  | 1 | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Dog Address Name |  | ho chi minh | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |





```
{
  "dogAddressId": 1,
  "dogAddressName": "ho chi minh"
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
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
}
```

