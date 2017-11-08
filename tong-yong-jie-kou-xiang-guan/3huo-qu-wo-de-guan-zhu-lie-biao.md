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
                    "token": "MTc4MTUxMDExMzI0NAo=",
                    "state": 1,
                    "userSig": "eJxlz11PgzAUgOF7fkXDrUbb0gYx8QLRsE4hwGB*3DR8FNYRGLCyaIz-fRM1knhun-fk5HxoAAA9flxdpHm*G1vF1XsndHANdKif-2HXyYKnihtD8Q-FWycHwdNSiWFCRCnFEM4bWYhWyVL*FubVDPdFzacL30ZOq4RYEM8TWU3o3ScOCx0vf1mixTq87La*-2Tm7AGl-UY6r4O38bJYBs2duy7tMepDVjnYL1nCoiCICGb1sq7Gs1vTiL2c2En03G*ThZvZbtasyM3spJKN*HkHWhaFiJgzPYhhL3ftFGCIKMIG-Bpd*9SOO29aug__",
                    "registerTime": 1509950141018,
                    "loginTime": 1510113254,
                    "logoutTime": null,
                    "lastRequestTime": 1510113254,
                    "currentAppId": "1400044902",
                    "phone": "178"
                },
                "roomNum": -1,
                "avtive": false
            },
            {
                "user": {
                    "id": "889",
                    "pwd": "MTIzNDU2",
                    "sid": "000004",
                    "username": "jjj",
                    "sex": null,
                    "age": null,
                    "imgUrl": "https://wx4.sinaimg.cn/mw690/006CMBjNly1fl4sy6pdcyj30ku0q1ar9.jpg",
                    "signature": null,
                    "token": "ODg5Cg==",
                    "state": 1,
                    "userSig": "eJxlj01Pg0AURff8iglbjR0*xoKJC1CK0jZtBax1M6Ew1IcZOg5j1Rr-uxWbOIlve87Nve-TQAiZ2SQ9K8py*9oqqj4EM9EFMrF5*geFgIoWijqy*gfZuwDJaFErJntoEUJsjHUHKtYqqOFoeJ6vwa56pn3Db9o9RF3Xx7auwKaH0yi-ur3mg2Y82swnMz*t9-EijO4X67mMH8Wog6yCLKzHoTtdPpwkAUSB94K508jVU-nW7fk5506Q8gGQu5vETpp4rfKVP1zuIjnLL7VKBZwd37Ewdog11DfvmOxg2-aCjQ*K7eCfM40v4xuLI1t3",
                    "registerTime": 1510035178603,
                    "loginTime": 1510035179,
                    "logoutTime": null,
                    "lastRequestTime": 1510109084824,
                    "currentAppId": "1400044902",
                    "phone": "889"
                },
                "roomNum": -1,
                "avtive": false
            }
        ],
        "userNumber": 2
        
    },
    "errorCode": "0",
    "errorInfo": ""
}
```

* response字段

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| following | Array | 关注用户数组 |
| userNumber | Integer | 人数 |

* follow数组字段

| 字段 | 类型 | 说明 |
| :---: | :---: | :---: |
| user | User | 用户对象 |
| active | Boolean | 用户是否在线 |
| roomNum | Integer | 用户在的房间号 |

> 本接口的用户是否在线仅仅指的是主播用户,若该用户不是主播则默认为该用户不在线



