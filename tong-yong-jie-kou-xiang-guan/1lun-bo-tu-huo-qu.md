#### 获取轮播图片列表

* 请求url

> [http://118.31.2.202:8080/zhibo/ad/getAdList](http://118.31.2.202:8080/ad/getAdList)

* response返回示例

```json
{
    "errorInfo": "",
    "data": {
        "adList": [
            {
                "id": "2c9024295f85ed6a015f85edfee30007",
                "createDate": 1509780487000,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "title": "aa",
                "url": "http://118.31.2.202:8081/productCategoryImg/andreas-rønningen-w3lQVmuK8fw.jpg"
            },
            {
                "id": "2c9024295f85fa5e015f85fbf0c50007",
                "createDate": 1509781401000,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "title": "aa",
                "url": "http://118.31.2.202:8081/productCategoryImg/2017.10.10-1.jpg"
            },
            {
                "id": "2c9024295f861c73015f861d001a0007",
                "createDate": 1509783568000,
                "modifyDate": null,
                "creater": null,
                "modifier": null,
                "title": "heihei",
                "url": "http://118.31.2.202:8081/productCategoryImg/2017-11-04/16-19andreas-rønningen-w3lQVmuK8fw.jpg"
            }
        ]
    },
    "errorCode": "0"
}
```

request示例:

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| adList | Array | 轮播图片列表 |

轮播图重要字段

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| url | String | 轮播图片链接 |



