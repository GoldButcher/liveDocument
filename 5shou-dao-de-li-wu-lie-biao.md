#### 收到的礼物列表以及用户信息

* 请求url

> http://118.32.2.202:8080/zhibo/giftRecord/userReceiveAndInfo

* request字段示例

```
{
    "userId":"11"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| userId | String | 必填 | 用户id |

* response字段示例

```
{
    "data": {
        "userInfo": {
            "id": "589",
            "pwd": "NTg5",
            "sid": "000001",
            "username": "哈哈",
            "sex": null,
            "age": null,
            "imgUrl": "https://wx4.sinaimg.cn/mw690/006CMBjNly1fl4sy6pdcyj30ku0q1ar9.jpg",
            "signature": null,
            "token": "NTg5MTUxMDEyNjIwNgo=",
            "state": 1,
            "userSig": "eJxlj0FPgzAAhe-8iqbXGWmhzaiJB*JQNsecGaCeGoRiOpHVUsec8b9v4hKb*K7f9-LyvhwAAEznq-OiLDcfreHmUwkILgBE8OwPKiUrXhju6*ofFDslteBFbYQeIKaUegjZjqxEa2QtTwYNmAW76pUPC79tcqwSwpBnK-JlgEmUXU1vhJuGOli8r0esmPVl7mfT1cOY6Kbxaxw1xE0el2m*u1P7UEYhwnGq9iMSP4-b7cxV9*sJnfQ9uc7nSxRpk90umuApSro4ubQmjXwTpzuIMYpwgC26FbqTm3YQPIQp9nz0E*h8OwcQN1p0",
            "registerTime": 1509950177940,
            "loginTime": 1510126436,
            "logoutTime": null,
            "lastRequestTime": 1510126436,
            "currentAppId": "1400044902",
            "phone": "589"
        },
        "userReceive": [
            {
                "name": "飞机哦",
                "imgUrl": "http://192.168.31.216:8080/bikexImg/product/2017-11-07-09/40-24-2017.10.10-2.jpg",
                "number": 3
            }
        ]
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| userInfo | User对象 | 用户信息 |
| userReceive | Array | 收到的礼物信息 |

userReceive数组对象

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| name | String | 礼物名字 |
| imgUrl | String | 礼物图片地址 |
| number | Integer | 收到的礼物数量 |



