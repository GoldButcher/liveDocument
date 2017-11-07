#### 修改房间标题

* 请求url

> [http://118.32.2.202:8080/zhibo/loveroom/editTitle](http://118.32.2.202:8080/zhibo/loveroom/editTitle)

* request字段示例

```
{
    "roomId":111,
    "title":"厉害"
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| roomNum | Integer | 必填 | 房间号ID |
| title | String | 必填 | 房间标题 |

* response字段示例

```json
{
    "errorInfo": "",
    "data": {},
    "errorCode": "0"
}
```



