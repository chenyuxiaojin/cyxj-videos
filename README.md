# cyxj-videos · 陈与小金的视频幕后

每期视频是怎么做出来的：用了什么模型、AI 做了什么、花了多少钱、学到了什么。

**在线看：https://chenyuxiaojin.github.io/cyxj-videos/**

## 各期

| 日期 | 视频 | 幕后 |
|---|---|---|
| 2026-09-30 | Opus 5.5 想得越久，画面越有艺术感吗？同一个题目，四个档位各做一遍 | [网页](https://chenyuxiaojin.github.io/cyxj-videos/2026-09-30-opus55/) · [文字版](2026-09-30-opus55/index.md) |

<a href="https://chenyuxiaojin.github.io/cyxj-videos/2026-09-30-opus55/"><img src="2026-09-30-opus55/cover.jpg" width="560" alt="Opus 5.5 思考档位盲测封面"></a>

**这一期的结论：** 同一个提示词，max 比 medium 多花约 7 倍时间，盲看却分不出来；真正让画面变样的是把旁白换成了一段第一人称、有转折、问句收尾的话。除了出镜录口播，活几乎都是 AI 干的：6 天里作者发了 251 条消息，Claude Code 执行了 2,352 次操作。

## 目录

每期一个文件夹 `YYYY-MM-DD-英文短名/`：

- `index.html`：幕后页（网页版）
- `index.md`：同内容的文字版，方便 AI 和搜索读取
- `cover.jpg`：视频封面
- `img/`：页面用到的画面截图

## 加新一期

1. 建 `YYYY-MM-DD-英文短名/`，放 `index.html`、`index.md`、`cover.jpg`、`img/`。
2. 首页 `index.html` 的封面墙、本 README 的表格、`llms.txt`、`sitemap.xml` 各加一条。
3. 只放幕后页和封面。不放工程代码、原始素材、镜头库和品牌设计文件。
