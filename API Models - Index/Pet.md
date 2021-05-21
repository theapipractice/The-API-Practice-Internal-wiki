# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Pet |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Order id |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Category |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Order id |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Category name |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Category name |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; photoUrls |  |  -  | No | No | No | No |  |Data Type : array<br>  |
| &gt; 0 |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; tags |  |  -  | No | No | No | No |  |Data Type : array<br>  |
| &gt; Category |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Order id |  |  -  | No | No | No | No |  |Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| &gt; Category name |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; status |  |  -  | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br> Enum : placed, approved, delivered<br>  |





```
{
  "id": 0,
  "category": {
    "id": 0,
    "name": ""
  },
  "name": "",
  "photoUrls": [
    ""
  ],
  "tags": [
    {
      "id": 0,
      "name": ""
    }
  ],
  "status": "placed"
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Pet",
  "type": "object",
  "additionalProperties": true,
  "properties": {
    "id": {
      "title": "Order id",
      "type": "integer",
      "additionalProperties": true
    },
    "category": {
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
    },
    "name": {
      "title": "Category name",
      "type": "string",
      "additionalProperties": true
    },
    "photoUrls": {
      "title": "photoUrls",
      "type": "array",
      "additionalProperties": true,
      "items": {
        "title": "0",
        "type": "string",
        "additionalProperties": true
      }
    },
    "tags": {
      "title": "tags",
      "type": "array",
      "additionalProperties": true,
      "items": {
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

