#### 用户收到的礼物数量

* 请求url

> [http://118.32.2.202:8080/zhibo/giftRecord/receiveGiftNumber](http://118.32.2.202:8080/zhibo/giftRecord/receiveGiftNumber)

* request字段示例

```Json
{
    "userId":"111"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| userId | String | 必填 | 用户id |

* response字段示例

```Json
{
    "data": {
        "receiveNumber": 0
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| receiverNumber | String | 必填 | 收到的礼物数量 |



