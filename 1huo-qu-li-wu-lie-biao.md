#### 获取礼物列表

* 请求Url

> http://118.32.2.202:8080/zhibo/gift/getGiftList



response字段示例

```Json
{
    "data": {
        "gifts": [
            {
                "id": "40289f585f9420a6015f9422872f001a",
                "createDate": 1510018811000,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "name": "aa",
                "price": 22,
                "imgUrl": "http://192.168.31.216:8080/bikexImg/product/2017-11-07-09/40-01-2017.10.10-2.jpg",
                "momo": ""
            },
            {
                "id": "40289f585f9420a6015f9422c8c6001e",
                "createDate": 1510018828000,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "name": "飞机哦",
                "price": 111111,
                "imgUrl": "http://192.168.31.216:8080/bikexImg/product/2017-11-07-09/40-24-2017.10.10-2.jpg",
                "momo": "很贵的"
            }
        ]
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

Gift类型

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| id | String | 礼物id |
| name | String | 礼物名字 |
| price | Decimal | 礼物价格 |
| imgUrl | String | 礼物图片地址 |
| momo | String | 礼物介绍 |



