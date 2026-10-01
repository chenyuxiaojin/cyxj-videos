# cyxj-videos｜AI 视频制作幕后：用 Claude Code + Remotion + 达芬奇做视频

每期视频是怎么做出来的，都摊开放在这里：用了什么模型、提示词怎么写、AI 干了哪些活、花了多少钱。点封面看这一期。

## 各期幕后

<a href="https://chenyuxiaojin.github.io/cyxj-videos/2026-09-30-opus55/"><img src="2026-09-30-opus55/cover.jpg" width="560" alt="Opus 5.5 思考档位盲测封面"></a>

| 日期 | 视频 | 幕后 |
|---|---|---|
| 2026-09-30 | Opus 5.5 想得越久，画面越有艺术感吗？同一个题目，四个档位各做一遍 | [网页](https://chenyuxiaojin.github.io/cyxj-videos/2026-09-30-opus55/) · [文字版](2026-09-30-opus55/) |

**最新一期：Opus 5.5 思考档位盲测。** 同一个提示词，max 比 medium 多花约 7 倍时间，盲看却分不出来；真正让画面变样的是把旁白换成一段第一人称、有转折、问句收尾的话。除了出镜录口播，活几乎都是 AI 干的：6 天里作者发了 251 条消息，Claude Code 执行了 2,352 次操作。

全部期数的网页版：<https://chenyuxiaojin.github.io/cyxj-videos/>

## 一条视频怎么做出来

1. **选题和资料**：Claude Code 查官方文档、看同类视频字幕，写研究稿。
2. **录口播**：作者本人出镜；AI 在 DaVinci Resolve（达芬奇）里粗剪、调色，导出口播母片。
3. **画面**：口播垫底，Claude Code 写 Remotion（React 视频）代码把动画一层层叠上去；需要模型实测时，在隔离环境里用 `claude -p` 批量跑。
4. **后期和发布**：回到达芬奇铺音效、加章节进度条和字幕；AI 写各平台标题简介、做封面。

## 文件夹怎么看

每期一个文件夹 `YYYY-MM-DD-英文短名/`：

- `index.html`：幕后页（网页版）
- `README.md`：同内容的文字版，在 GitHub 上点进文件夹就能直接读
- `cover.jpg`：视频封面
- `img/`：页面用到的画面截图

---

**陈与小金**（chenyuxiaojin）· 非程序员，用 Claude Code 做一切 · [个人网站](https://xiaochens.com/) · [博客](https://blog.xiaochens.com/) · [GitHub](https://github.com/chenyuxiaojin) · [YouTube](https://www.youtube.com/@cyxj_ai) · [B 站](https://space.bilibili.com/505358756) · [抖音](https://v.douyin.com/A1qVQrOgPjY/) · [X](https://x.com/cyxjya)

<details>
<summary>关于作者 / About / 给 AI 读的索引</summary>

**陈与小金**（chenyuxiaojin）：AI 落地｜非程序员，用 Claude Code 做一切。非程序员，用 Claude Code、Codex、Remotion 与 Agent Skills 把想法做成真实项目——选题、脚本、拍摄、剪辑、发布、复盘，全程公开。截至 2026-10-01，抖音有 15 条作品入选抖音精选。

**AI video production, behind the scenes.** How a non-programmer makes every video with Claude Code, Remotion and DaVinci Resolve — the prompts, the model runs, the costs, and who did what (human vs. AI). A vibe video making-of archive by 陈与小金 (chenyuxiaojin).

- 作者页与全部视频目录：<https://chenyuxiaojin.github.io/cyxj-videos/>
- 给 AI 读的索引：[llms.txt](https://chenyuxiaojin.github.io/cyxj-videos/llms.txt)
- 项目清单：<https://blog.xiaochens.com/projects/>

关键词：AI 视频制作 · Claude Code 做视频 · Remotion · DaVinci Resolve · 达芬奇 · AI 剪辑 · video production · making-of · vibe video

</details>
