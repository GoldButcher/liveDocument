#### 修改位置信息

* 请求url

> [http://118.32.2.202:8080/zhibo/roomAccount/setSeat](http://118.32.2.202:8080/zhibo/roomAccount/setSeat)

* request字段示例

```json
{
    "roomId":"111",
    "tag" : 1,
    "userId":"11",
    "imgSrc":"xxxx",
    "renStatus":false,
    "maiStatus":true,
    "enableStatus":false,
    "name":"洪东健"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| roomId | String | 必填 | 房间id |
| tag | Integer | 必填 | 座位号 |



* response字段示例

```json
{
    "data": {
        "id": "2c9024295f8ee953015f8f3b8b370002",
        "createDate": 1509936565000,
        "modifyDate": null,
        "creater": null,
        "modifier": null,
        "imgSrc": "xxxx",
        "renStatus": false,
        "maiStatus": true,
        "enableStatus": true,
        "tag": 1,
        "name": "洪东健",
        "roomId": "178",
        "userId": "11"
    },
    "errorCode": "0",
    "errorInfo": ""
}
```



