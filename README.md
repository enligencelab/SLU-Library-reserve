# SLU_Library_reserve
自动预约SLU图书馆座位

## config.json参数说明
```json
{
  "username": "",  填写你的学号
  "password": "",  填写你的密码
  "habit": [
    {
      "room": "Mulan_2F_book",  房间参数
      "seat_id": "PDT2FSK120",  座位编号
      "day": "today",  （tomorrow 或者 today） 预约日期（今明两天）
      "bt": "09:30:00",   开始时间
      "et": "22:30:00"    结束时间
    }
  ]
}
```

## 木兰图书馆room参数
|  room   | 具体位置  |
|  ----  | ----  |
| Mulan_1F_101  | 101阅览室 |
| Mulan_1F_102  | 102阅览室 |
| Mulan_1F_book  | 一楼书库 |
| Mulan_2F_book  | 二楼书库 |
| Mulan_2F_data  | 二楼数字体验空间 |
| Mulan_3F_book  | 三楼书库 |

## 文博楼room参数
|  room   | 具体位置  |
|  ----  | ----  |
| Wenbo_3F_A_1  | 三楼阅览室A-1区 |
| Wenbo_3F_A_2  | 三楼阅览室A-2区 |
| Wenbo_3F_A_3  | 三楼阅览室A-3区 |
