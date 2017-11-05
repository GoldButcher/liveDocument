#### 获取房间列表信息

* 请求url

[http://118.31.2.202:8080/zhibo/roomAccount/](http://118.31.2.202:8080/zhibo/roomAccount/create)get

request字段示例

```json
{
    "roomId":"111"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| roomId | String | 必填 | 房间ID，用于获取房间信息 |

response字段示例

```json
{
    "data": {
        "roomId": "111",
        "seats": [
            {
                "id": "40289f585f870cdd015f8713167e0001",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 0,
                "name": null
            },
            {
                "id": "40289f585f870cdd015f871316ce0002",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 1,
                "name": null
            },
            {
                "id": "40289f585f870cdd015f871316cf0003",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 2,
                "name": null
            },
            {
                "id": "40289f585f870cdd015f871316d00004",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 3,
                "name": null
            },
            {
                "id": "40289f585f870cdd015f871316d10005",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 4,
                "name": null
            },
            {
                "id": "40289f585f870cdd015f871316d10006",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 5,
                "name": null
            },
            {
                "id": "40289f585f870cdd015f871316d20007",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 6,
                "name": null
            },
            {
                "id": "40289f585f870cdd015f871316d30008",
                "createDate": null,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "imgSrc": null,
                "renStatus": false,
                "maiStatus": true,
                "enableStatus": false,
                "tag": 7,
                "name": null
            }
        ],
        "number": 1
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| roomId | String | 房间ID |
| number | Interger | 房间内总人数至少为1\(主播\) |
| seats | Array | 房间位置信息一共8个位置 |

seat对象

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| id | String | 房间id |
| createDate | Date | 创建时间 |
| modifyDate | Date | 修改时间 |
| creater | String | / |
| modifier | String | / |
| imgSrc | String | 成员头像 |
| renStatus | Boolean | 标识是否有人 |
| maiStatus | Boolean | 标识是否禁麦 |
| enableStatus | Boolean | 标识位置是否被封闭 |
| tag | Integer | 位置编号\(0-7\) |
| name | String | 该位置成员昵称 |



