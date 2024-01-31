# 今日热榜

汇聚全网热点，热门尽览无余。

## 快速启动

使用如下代码启动后，浏览器访问 <http://your-domain>

```shell
docker run -d -p 80 -p 443 \
    -e APP_COPYRIGHT="Example" \
    -e APP_COPYRIGHT_URL="http://www.example.org" \
    rehiy/dailyhot
```

## 接口总览

> 🟢 状态正常
> 🟠 可能失效
> ❌ 无法使用

| **站点**     | **类别** | **调用名称**          | **状态** |
| ------------ | -------- | --------------------- | -------- |
| 哔哩哔哩     | 热门榜   | bilibili              | 🟢        |
| 微博         | 热搜榜   | weibo                 | 🟢        |
| 知乎         | 热榜     | zhihu                 | 🟢        |
| 百度         | 热搜榜   | baidu                 | 🟢        |
| 抖音         | 热点榜   | douyin / douyin_new   | 🟢        |
| 抖音         | 热歌榜   | douyin_music          | 🟢        |
| 豆瓣         | 新片榜   | douban_new            | 🟢        |
| 豆瓣讨论小组 | 讨论精选 | douban_group          | 🟢        |
| 百度贴吧     | 热议榜   | tieba                 | 🟢        |
| 少数派       | 热榜     | sspai                 | 🟢        |
| IT 之家      | 热榜     | ithome                | 🟠        |
| 澎湃新闻     | 热榜     | thepaper              | 🟢        |
| 今日头条     | 热榜     | toutiao               | 🟢        |
| 36 氪        | 热榜     | 36kr                  | 🟢        |
| 稀土掘金     | 热榜     | juejin                | 🟢        |
| 腾讯新闻     | 热点榜   | newsqq                | 🟢        |
| 网易新闻     | 热点榜   | netease               | 🟢        |
| 英雄联盟     | 更新公告 | lol                   | 🟢        |
| 原神         | 最新消息 | genshin               | 🟢        |
| 微信读书     | 飙升榜   | weread                | 🟢        |
| 快手         | 热榜     | kuaishou              | 🟢        |
| 网易云音乐   | 排行榜   | netease_music_toplist | 🟢        |
| QQ音乐       | 排行榜   | qq_music_toplist      | 🟢        |
| NGA          | 热帖     | ngabbs                | 🟢        |
| Github       | Trending | github                | 🟢        |
| V2EX         | 热榜     | v2ex                  | 🟠        |
| 历史上的今天 | 指定日期 | calendar              | 🟢        |

## 上游项目

感谢上游源码维护者的无私奉献。

- <https://github.com/imsyy/DailyHot>
  
- <https://github.com/imsyy/DailyHotApi>
