#### 该用户是否关注对方

* 请求url

> [http://118.32.2.202:8080/zhibo/follow/isFollow](http://118.32.2.202:8080/zhibo/follow/isFollow)

* request字段示例

```
{
    "userId":"889",
    "followed":"178"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| userId | String | 必填 | 用户id |
| followed | String | 必填 | 查询对方id |

* response字段示例

```
{
    "data": {
        "isFollow": true
    },
    "errorCode": "0",
    "errorInfo": ""
}
```



