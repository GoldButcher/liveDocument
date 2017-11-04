#### 使用id号获取用户信息

* 请求url:

> [http://118.31.2.202:8080/zhibo/user/getInfo](http://118.31.2.202:8080/zhibo/user/getInfo)

* request字段示例

```json
{
"id":"1111",
"token":"aaaa="
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| id | String | 必填 | 用户ID |
| token | String | 必填 | 用户登录获得的token |

response字段示例

```json
{
    "data": {
        "id": "111",
        "pwd": "MQ==",
        "sid": "000003",
        "userName": null,
        "sex": null,
        "age": null,
        "imgUrl": null,
        "token": "MTExCg==",
        "state": 1,
        "userSig": "eJxlz11PgzAUgOF7fgXhVmPajjox8WKQxo3BmGMfiTeEjVJPyKChFbYs-ncdamziuX3ek5NzsWzbdtZRepcfDs17rTN9ltyxH20HObd-KCUUWa6zUVv8Q36S0PIsLzVvB8SUUoKQ2UDBaw0l-BYYG6iKKhsufJv7teq6HiJmAmLAmG2CWRBub0Q3RVCpt1kSROf9s0yDl47hcd42e0WXfRHXMevcZAJsQn3Ur4WMhQa1iERZ*WmIwu1unixPq3HPyHwHr4vk6E83T8ZJDUf*8w7y7h88QjxDO94qaOohIAhTTEboOo71YX0Cq8pbxQ__",
        "registerTime": 1509681784203,
        "loginTime": 1509689229,
        "logoutTime": null,
        "lastRequestTime": 1509689229,
        "currentAppId": "1400044902",
        "phone": "111",
        "signature":"666666"
    },
    "errorCode": "0",
    "errorInfo": ""
}
```



