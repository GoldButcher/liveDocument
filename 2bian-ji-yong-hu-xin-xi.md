#### 编辑用户信息

* 请求url

> [http://118](http://118).31.2.202:8080/zhibo/user/editInfo

* request字段示例

```json
{
    "id":"111",
    "username":"111",
    "sex":"男",
    "age":16,
    "imgUrl":"xxxxxx",
    "signature":"666666"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| id | String | 必填 | 用户id |
| username | String | 必填 | 用户名 |
| sex | String | 必填 | 用户性别 |
| age | Integer | 必填 | 用户年龄 |
| imgUrl | String | 必填 | 用户头像 |
| signature | String | 必填 | 用户个性签名 |

* response字段示例

```json
{
    "data": {},
    "errorCode": "0",
    "errorInfo": ""
}
```



