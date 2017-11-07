#### 获取房间内用户

* 请求url

> [http://118.32.2.202:8080/zhibo/roomAccount/getUsers4Room](http://118.32.2.202:8080/zhibo/roomAccount/getUsers4Room)

* request字段示例

```Json
{
    "roomNum":256,
    "role":1,
    "first":0,
    "max":10
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| roomNum | Integer | 必填 | 房间号 |
| role | Integer | 必填 | 权限号\(1.主播,2.未上麦成员,3.上麦成员\) |
| first | Integer | 必填 | 分页第一条数据编号 |
| max | Integer | 必填 | 分页每条信息数 |

* response字段示例

```
{
    "data": {
        "users": [
            {
                "id": "1",
                "pwd": "11",
                "sid": "000001",
                "username": "哈哈",
                "sex": null,
                "age": null,
                "imgUrl": "https://wx4.sinaimg.cn/mw690/006CMBjNly1fl4sy6pdcyj30ku0q1ar9.jpg",
                "signature": null,
                "token": "token",
                "state": 1,
                "userSig": "userSig"
                "registerTime": 1509950177940,
                "loginTime": 1510035876,
                "logoutTime": null,
                "lastRequestTime": 1510035914,
                "currentAppId": "1400044902",
                "phone": "589"
            }
        ],
        "userNumber":1
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| users | Array | 用户数组 |
| userNumber | Integer | 房间内用户人数 |



