#### 获取我的关注列表

* 请求url

> [http://118.32.2.202:8080/zhibo/follow/getMyFollowing](http://118.32.2.202:8080/zhibo/follow/following)

* request请求字段示例

```Json
{
    "userId":"111",
    "first":0,
    "max":10
}
```

| 字段 | 类型 | 选项 | 说明 |
| :---: | :---: | :---: | :---: |
| userId | String | 必填· | 用户id |
| first | Integer | 必填 | 分页第一条数据编号 |
| max | Integer | 必填 | 分页每页数据数量 |

* response字段示例

```
{
    "data": {
        "following": [
            {
                "user": {
                    "id": "178",
                    "pwd": "MTc4",
                    "sid": "000000",
                    "username": "呵呵",
                    "sex": "男",
                    "age": 0,
                    "imgUrl": "https://wx4.sinaimg.cn/mw690/006CMBjNly1fl4sy6pdcyj30ku0q1ar9.jpg",
                    "signature": "",
                    "token": "MTc4MTUxMDEyMDE3NQo=",
                    "state": 1,
                    "userSig": "eJxlz11PgzAUgOF7fkXDrUbb0gYx8QLRsE4hwGB*3DR8FNYRGLCyaIz-fRM1knhun-fk5HxoAAA9flxdpHm*G1vF1XsndHANdKif-2HXyYKnihtD8Q-FWycHwdNSiWFCRCnFEM4bWYhWyVL*FubVDPdFzacL30ZOq4RYEM8TWU3o3ScOCx0vf1mixTq87La*-2Tm7AGl-UY6r4O38bJYBs2duy7tMepDVjnYL1nCoiCICGb1sq7Gs1vTiL2c2En03G*ThZvZbtasyM3spJKN*HkHWhaFiJgzPYhhL3ftFGCIKMIG-Bpd*9SOO29aug__",
                    "registerTime": 1509950141018,
                    "loginTime": 1510120185,
                    "logoutTime": null,
                    "lastRequestTime": 1510120727,
                    "currentAppId": "1400044902",
                    "phone": "178"
                },
                "liveRoom": {
                    "id": 335,
                    "appid": 1400044902,
                    "cover": "https://wx4.sinaimg.cn/mw690/006CMBjNly1fl4sy6pdcyj30ku0q1ar9.jpg",
                    "chatRoomId": "368",
                    "hostUid": "178",
                    "longitude": 0,
                    "latitude": 0,
                    "address": "",
                    "admireCount": 0,
                    "createTime": "1510120592223",
                    "modifyTime": "1510120732",
                    "avRoomId": 368,
                    "title": "呵呵",
                    "roomType": "live",
                    "device": 0,
                    "videoType": 0,
                    "playUrl1": "rtmp://123456.liveplay.myqcloud.com/live/123456_9eb1d36835d6d1ba1d59a377f58e34b9",
                    "playUrl2": "http://123456.liveplay.myqcloud.com/live/123456_9eb1d36835d6d1ba1d59a377f58e34b9.flv",
                    "playUrl3": "http://123456.liveplay.myqcloud.com/live/123456_9eb1d36835d6d1ba1d59a377f58e34b9.m3u8"
                },
                "avtive": true
            }
        ]
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

* response字段

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| following | Array | 关注用户数组 |

* follow数组字段

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| user | User | 用户对象 |
| active | Boolean | 用户是否在线 |
| liveRoom | LiveRoom | 用户房间信息 |

> 本接口的用户是否在线仅仅指的是主播用户,若该用户不是主播则默认为该用户不在线



