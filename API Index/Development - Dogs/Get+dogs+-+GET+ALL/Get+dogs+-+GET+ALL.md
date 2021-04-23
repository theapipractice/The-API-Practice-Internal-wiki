# Get dogs - GET ALL

GET /v1/dogs

## Description



* [Request Payloads](#request-payloads)
* [Response Payloads](#response-payloads)

| HTTP Method                           | Get|
| ------------------------------------- | ----------------------------------------------- |
| API                                   | Dogs                                           |
| Api Version                           | 1.0.0.10                                         |
| Resource Version                      | 1                                               |
| Summary                               |                                       |
| Base Path                             | /v1/dogs                                     |
| Resource                              | Get dogs                                      |
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
| >Limit |  | 20 | No | No | No | No |  -  | Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| >Offset |  | 0 | No | No | No | No |  -  | Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |


---

### Request Body

#### Payload 



| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :----- |
| Request Payload |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |



#### Json sample
```
{}
```


#### Json Schema
```
{
  "title": "Request Payload",
  "type": "object"
}
```

---