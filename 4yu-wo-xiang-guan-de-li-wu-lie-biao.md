#### 与我相关的礼物列表

* 请求url

> [http://118.32.2.202:8080/zhibo/giftRecord/myGiftRecord](http://118.32.2.202:8080/zhibo/giftRecord/myGiftRecord)

* request字段示例

```Json
{
    "userId":"178"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| userId | String | 必填 | 用户id |

* response字段示例

```Json
{
    "data": {
        "giftRecords": [
            {
                "id": "40289f585f94426b015f9444ccad0004",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "fromUserId": "178",
                "toUserId": "589",
                "giftId": "40289f585f9420a6015f9422872f001a",
                "number": 1
            },
            {
                "id": "40289f585f94426b015f9444ded10005",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "fromUserId": "178",
                "toUserId": "589",
                "giftId": "40289f585f9420a6015f9422872f001a",
                "number": 1
            },
            {
                "id": "40289f585f94426b015f9444e2ba0006",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "fromUserId": "178",
                "toUserId": "589",
                "giftId": "40289f585f9420a6015f9422872f001a",
                "number": 1
            },
            {
                "id": "40289f585f94426b015f9444e8380007",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "fromUserId": "178",
                "toUserId": "589",
                "giftId": "40289f585f9420a6015f9422872f001a",
                "number": 1
            }
        ]
    },
    "errorCode": "0",
    "errorInfo": ""
}
```



