#### 用户的礼物记录

* 请求url

> [http://118.32.2.202:8080/zhibo/giftRecord/userReceive](http://118.32.2.202:8080/zhibo/giftRecord/userReceive)\(收到的礼物\)
>
> [http://118.32.2.202:8080/zhibo/giftRecord/userSend\(送出的礼物](http://118.32.2.202:8080/zhibo/giftRecord/userSend%28送出的礼物\)\)

* request字段示例

```
{
    "userId":"178",
    "first":0,
    "max":1
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| userId | String | 必填 | 用户Id |
| first | Integer | 必填 | 分页第一条数据编号 |
| max | Integer | 必填 | 分页每条数量 |

* response字段示例

```
{
    "data": {
        "total": 3,
        "giftRecords": [
            {
                "id": "40289f585f9acdc8015f9acf5bbd0004",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "fromUserId": "178",
                "toUserId": "589",
                "giftId": "40289f585f9420a6015f9422c8c6001e",
                "number": 1,
                "imgUrl": "http://192.168.31.216:8080/bikexImg/product/2017-11-07-09/40-24-2017.10.10-2.jpg",
                "name": "飞机哦"
            }
        ]
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| total | Integer | 总记录数 |
| giftRecords | Array | 记录数组 |



