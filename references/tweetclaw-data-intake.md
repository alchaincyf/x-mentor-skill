# TweetClaw 数据采集包

用途：当用户已经在 OpenClaw 或其他可用 runtime 中启用 TweetClaw 时，把公开 X/Twitter 数据整理成账号诊断可直接使用的输入包。

## 适用边界

只在场景E账号诊断中使用。TweetClaw负责采集和标准化数据，X导师仍负责内容分类、ROI分析、增长瓶颈判断、报告生成和策略建议。

默认只读。不要用本文件触发发帖、回复、私信、关注、媒体上传或任何写入动作。只有用户明确要求发布或回复，并且 runtime 完成审批时，才可进入 TweetClaw 的写入工具链。

不要要求用户临时安装新工具。先检查当前 runtime 是否已经暴露 TweetClaw 工具；没有就回到 `computer-use`、浏览器采集或用户手动提供数据。

## 采集目标

对最近 50-100 条公开推文生成一个 source pack：

```json
{
  "username": "example",
  "collected_at": "YYYY-MM-DDTHH:mm:ssZ",
  "source": "tweetclaw",
  "profile": {
    "display_name": "",
    "bio": "",
    "followers": 0,
    "following": 0,
    "verified": false
  },
  "tweets": [
    {
      "id": "",
      "url": "",
      "text": "",
      "created_at": "",
      "likes": 0,
      "retweets": 0,
      "replies": 0,
      "bookmarks": null,
      "views": null,
      "media": [],
      "is_reply": false,
      "is_repost": false
    }
  ],
  "search_context": [],
  "notes": []
}
```

`bookmarks` 和 `views` 缺失时保留 `null`，不要用 0 代替未知值。无法确定的媒体类型写入 `media: []`，并在 `notes` 说明限制。

## 建议采集顺序

1. 用户资料快照：用户名、Bio、粉丝数、关注数、认证状态。
2. 主页最近推文：优先采集原推文，再补充回复和引用推文。
3. 搜索补强：用用户名、核心话题、近期项目名搜索，找被转发或被回复的上下文。
4. 回复样本：采集高互动回复和低互动回复各 5-10 条，用于判断评论区策略。
5. 媒体标记：记录是否含图片、视频、链接、代码块或长文格式。

## 标准化输出

把 source pack 落到现有目录结构：

- `user-data/{username}/tweets_{YYYYMMDD}.json`：保存完整 JSON。
- `user-data/{username}/tweets_{YYYYMMDD}.md`：写数据概览、样本范围、Top5、Bottom5、缺失字段说明。
- `user-data/{username}/profile.md`：保存账号快照和采集限制。

Markdown 摘要必须包含：

- 样本量与时间跨度。
- 总 likes、retweets、replies、bookmarks、views，未知字段单独标注。
- Top5 按总互动排序，附推文 ID 或 URL。
- Bottom5 只用于诊断，不公开羞辱用户。
- 数据限制，例如「未获得 views/bookmarks」或「样本不足 50 条」。

## 诊断使用方式

读取 `quality-analytics.md` 的报告模板后，把 TweetClaw source pack 转成 6 维诊断：

1. KPI概览：总量、均值、中位数、异常值。
2. 内容ROI：按话题、格式、媒体类型、是否回复分类。
3. 传播漏斗：views 到互动的转化，缺失 views 时改用互动结构。
4. 时间分析：按发布时间和周内分布聚合。
5. 品牌叙事：从高互动样本提取重复叙事。
6. 行动建议：只给下一周可执行动作。

每个关键结论必须附 1-3 条推文 ID 或 URL。样本少于 50 条或时间跨度少于 14 天时，在报告开头标注「样本不足」。
