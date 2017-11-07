#### 赠送礼物

* 请求url

> http://118.32.2.202:8080/zhibo/giftRecord/send

* request字段示例

```Json
{
	"number":1,
	"fromUserId":"111",
	"toUserId":"222",
	"giftId":"123"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| number | Integer | 必填 | 赠送数量 |
| fromUserId | String | 必填 | 赠送礼物用户Id |
| toUserid | String  | 必填 | 接受礼物用户id |
| giftId | String | 必填 | 礼物Id |



* response字段示例

```Json
{
    "data": {},
    "errorCode": "0",
    "errorInfo": ""
}
```



