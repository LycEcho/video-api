# video-api
获取头条-百家-企鹅-大鱼（视频或则文章）url-免费api接口

### 官网在线体验:
http://video.lycecho.com/

### 请求API:
http://video.lycecho.com/get_list

### 请求方式:
GET

### 参数:

| 参数名  | 必选  | 类型  | 说明  |
| :------------: | :------------: | :------------: | :------------: |
| api  |  是 | num  | 值：1  |
|token	       |是|	string	|生成的Token|
|checkType	   |是|	num	    |平台类型：1头条 2百家 3 企鹅 4大鱼|
|checkHeader	   |是|	num	    |类型：1文章 2视频|
|count	       |否|	num	    |阅读量大于|
|commentsCount  |否|	num	    |评论量大于|
|str_time	   |否|	string	|开始时间 2020-02-01 21:01:01|
|end_time	   |否|	string	|结束时间 2020-02-01 21:01:01|
|original	   |否|	num	    |1=原创 2=非原创|
|search	       |否|	string	|搜索关键词，多个关键词逗号隔开|
|orderY	       |否|	num	    |排序，1阅读正序，2阅读倒序，3评论正序，4评论倒序|
|page	       |否|	num 	|分页量，1，2，3，4|


### 联系方式
<img src="http://cj.lycecho.com/article/wp-content/uploads/2022/10/%E5%BE%AE%E4%BF%A1%E5%8F%B7-220x300.jpg" width="200">


### 返回实例:
### 视频的实例
```json
{
    "state": 1,
    "mess": "ok",
    "data": [
        {
            "tag_c": "美食",
            "tag_e": "video_food",
            "id": "330385138",
            "title": "能当饭吃的甜品，感谢你们推荐，你们一定想让我多<font color='red'>吃饭</font>",
            "titles": "能当饭吃的甜品，感谢你们推荐，你们一定想让我多吃饭",
            "comments_count": "0",
            "is_shop": null,
            "is_shop_goods_id": null,
            "shop_check_id": null,
            "go_detail_count": "203",
            "digg_count": "26",
            "duration": "60",
            "want_count": 0,
            "collection": 0,
            "like_count": 0,
            "forward_count": 0,
            "comment_count": 0,
            "share_count": 0,
            "shop_name": 0,
            "spuid": 0,
            "behot_time": "1667276070",
            "behot_times": "1667276070",
            "group_id": "7160896193596555807",
            "yuanchuang": " <span><img class=\"original_icon\" style=\"cursor:pointer\" title=\"原创文章\" src=\"http://cdnnew.51taojinge.com/Static/images/index/original_icon.png\" alt=\"原创\" /></span>",
            "checkStr": 2,
            "url": "https://www.ixigua.com/7160896193596555807/"
        }, {
            "tag_c": "搞笑",
            "tag_e": "video_funny",
            "id": "330384606",
            "title": "喝汽水场面合集：赵本山喝汽水这段，建议边<font color='red'>吃饭</font>边看，吃得太香了",
            "titles": "喝汽水场面合集：赵本山喝汽水这段，建议边吃饭边看，吃得太香了",
            "comments_count": "0",
            "is_shop": null,
            "is_shop_goods_id": null,
            "shop_check_id": null,
            "go_detail_count": "3",
            "digg_count": "0",
            "duration": "941",
            "want_count": 0,
            "collection": 0,
            "like_count": 0,
            "forward_count": 0,
            "comment_count": 0,
            "share_count": 0,
            "shop_name": 0,
            "spuid": 0,
            "behot_time": "1667275043",
            "behot_times": "1667275043",
            "group_id": "7160575330300887563",
            "yuanchuang": " <span><img class=\"original_icon\" style=\"cursor:pointer\" title=\"原创文章\" src=\"http://cdnnew.51taojinge.com/Static/images/index/original_icon.png\" alt=\"原创\" /></span>",
            "checkStr": 2,
            "url": "https://www.ixigua.com/7160575330300887563/"
        },
        {
            "tag_c": "新闻",
            "tag_e": "news",
            "id": "330385434",
            "title": "给老铁拆解一根油压带电感的别克减震器，直播<font color='red'>中</font>（上）#别克电感减震器 #别克仰角 #别克卡钳 #别克ABS传感器 #别克拆车件",
            "titles": "给老铁拆解一根油压带电感的别克减震器，直播中（上）#别克电感",
            "comments_count": "0",
            "is_shop": null,
            "is_shop_goods_id": null,
            "shop_check_id": null,
            "go_detail_count": "0",
            "digg_count": "0",
            "duration": "85",
            "want_count": 0,
            "collection": 0,
            "like_count": 0,
            "forward_count": 0,
            "comment_count": 0,
            "share_count": 0,
            "shop_name": 0,
            "spuid": 0,
            "behot_time": "1667282110",
            "behot_times": "1667282110",
            "group_id": "7160922092085562655",
            "yuanchuang": "",
            "checkStr": 2,
            "url": "https://www.ixigua.com/7160922092085562655/"
        },
    ]
}

```
### 文章的实例
```json
{
    "state": 1,
    "mess": "ok",
    "data": [
        {
            "tag_c": "美食",
            "tag_e": "news_food",
            "id": "186092384",
            "title": "湖南一父亲给女儿做饭 家人：<font color='red'>吃饭</font>像开盲盒",
            "titles": "湖南一父亲给女儿做饭 家人：吃饭像开盲盒",
            "comments_count": "0",
            "is_shop": "0",
            "is_shop_goods_id": null,
            "shop_check_id": "0",
            "go_detail_count": "14",
            "digg_count": "0",
            "duration": null,
            "want_count": 0,
            "collection": 0,
            "like_count": 0,
            "forward_count": 0,
            "comment_count": 0,
            "share_count": 0,
            "shop_name": 0,
            "spuid": 0,
            "behot_time": "1667280449",
            "behot_times": "1667280449",
            "group_id": "7160915002210124292",
            "yuanchuang": "",
            "checkStr": 1,
            "url": "http://www.toutiao.com/a7160915002210124292/"
        },
        {
            "tag_c": "汽车",
            "tag_e": "news_car",
            "id": "186083142",
            "title": "奇瑞拿出诚意，轴距近2米8，入门鲲鹏1.6T，还能靠脸<font color='red'>吃饭</font>",
            "titles": "奇瑞拿出诚意，轴距近2米8，入门鲲鹏1.6T，还能靠脸吃饭",
            "comments_count": "0",
            "is_shop": "0",
            "is_shop_goods_id": null,
            "shop_check_id": "0",
            "go_detail_count": "0",
            "digg_count": "0",
            "duration": null,
            "want_count": 0,
            "collection": 0,
            "like_count": 0,
            "forward_count": 0,
            "comment_count": 0,
            "share_count": 0,
            "shop_name": 0,
            "spuid": 0,
            "behot_time": "1667275268",
            "behot_times": "1667275268",
            "group_id": "7160892702824219150",
            "yuanchuang": "",
            "checkStr": 1,
            "url": "http://www.toutiao.com/a7160892702824219150/"
        },
        {
            "tag_c": "育儿",
            "tag_e": "news_baby",
            "id": "186090751",
            "title": "2岁孩子<font color='red'>吃饭</font>粘了满身米，宝妈找“洗衣鸡”帮忙啄干净",
            "titles": "2岁孩子吃饭粘了满身米，宝妈找“洗衣鸡”帮忙啄干净",
            "comments_count": "0",
            "is_shop": "0",
            "is_shop_goods_id": null,
            "shop_check_id": "0",
            "go_detail_count": "2",
            "digg_count": "1",
            "duration": null,
            "want_count": 0,
            "collection": 0,
            "like_count": 0,
            "forward_count": 0,
            "comment_count": 0,
            "share_count": 0,
            "shop_name": 0,
            "spuid": 0,
            "behot_time": "1667275002",
            "behot_times": "1667275002",
            "group_id": "7160891497457238535",
            "yuanchuang": "",
            "checkStr": 1,
            "url": "http://www.toutiao.com/a7160891497457238535/"
        }
    ]
}
```