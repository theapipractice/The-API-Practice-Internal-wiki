# Update Dog - PUT ONE

PUT /v1/dogs

## Description



* [Request Payloads](#request-payloads)
* [Response Payloads](#response-payloads)

| HTTP Method                           | Put|
| ------------------------------------- | ----------------------------------------------- |
| API                                   | Dogs                                           |
| Api Version                           | 1.0.0.14                                         |
| Resource Version                      | 1                                               |
| Summary                               |                                       |
| Base Path                             | /v1/dogs                                     |
| Resource                              | Update Dog                                      |
| Endpoint URL                          | http://api.flowstep.dev/v1/dogs              |
| Service Status                        | Unknown                                         |
| Legislative / Regulatory / Compliance |                                             |
| Firewalls Details                     |                                              |
| Security Certificate Details          |                                              |
| Vendor or Partner Considerations      |                                             |

## Request Payloads

### Request Header



| Header | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| ------ | :---------: | :----: | :-: | :-------: | :---------------: | :-------: | :-----: | ------- |
| Api Header |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |


---

### Query Params



| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --------- | :---------: | :----: | :-: | :-------: | :---------------: | :-------: | :-----: | ------- |
| Api Query Parameter |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |


---

### Request Body

#### Payload 



| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :----- |
| Request Payload |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |
| >Dog |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |
| >>Dog Id |  | 1 | No | No | No | No |  -  | Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| >>Dog Name |  | kiki | No | No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br> Allow Null : false<br> Faker : name.firstName<br>  |
| >>Dog Address |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |
| >>>Dog Address Id |  | 1 | No | No | No | No |  -  | Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| >>>Dog Address Name |  | ho chi minh | No | No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| >>Dog Photos |  |  -  | No | No | No | No |  -  | Data Type : array<br>  |
| >>>Dog Photo |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |
| >>>>Dog Photo Id |  | 1 | No | No | No | No |  -  | Data Type : number<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| >>>>Dog Photo Name |  | aaaa | No | No | No | No |  -  | Data Type : string<br> Min. length : 1<br> Max. length : 50<br> Regex :  - <br> Allow Null : false<br> Faker : address.streetName<br>  |



#### Json sample
```
{
  "dog": {
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
}
```


#### Json Schema
```
{
  "title": "Request Payload",
  "type": "object",
  "properties": {
    "dog": {
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
                "additionalProperties": true
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
  }
}
```

---