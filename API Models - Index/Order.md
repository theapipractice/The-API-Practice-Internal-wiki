# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Order |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Order id |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; petId |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; quantity |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; shipDate |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; status |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br> Enum : placed, approved, delivered<br>  |
| &gt; complete |  |  -  | No | No | No | No |  |Data Type : boolean<br>  |





```
{
  "id": 0,
  "petId": 0,
  "quantity": 0,
  "shipDate": "",
  "status": "placed",
  "complete": false
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Order",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "id": {
      "title": "Order id",
      "type": "integer",
      "additionalProperties": true
    },
    "petId": {
      "title": "petId",
      "type": "integer",
      "additionalProperties": true
    },
    "quantity": {
      "title": "quantity",
      "type": "integer",
      "additionalProperties": true
    },
    "shipDate": {
      "title": "shipDate",
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
    },
    "complete": {
      "title": "complete",
      "type": "boolean",
      "additionalProperties": true
    }
  }
}
```

