# AI Search Visibility Audit — 免费方法论 + 工具

我们运营 **[https://956231studio.com](https://956231studio.com)** ：一套「让 AI 搜索（ChatGPT / Perplexity / Gemini / Claude）能找到你」的体检与修复服务。

## 为什么做这个

大多数网站在 AI 答案里「隐形」却不自知。我们做了一个**只读 12 项体检**
（robots.txt / llms.txt / JSON-LD / canonical / 可引用答案块 …），结果页公开可分享。

## 免费自检（无需注册）

👉 https://956231studio.com/geo-landing/

## 方法论：可量化三件套

1. **AI 引用率基线快照** —— 今天各引擎在哪些答案里引用你、引用的是谁。
2. **结构化内容 / 实体口径修复清单** —— 逐条到元素级。
3. **30 天引用率复测对比** —— 修复上线后同一测量再跑一遍，前后数字对比。

## 12 项体检（全部只读，不改你的站点）

| # | 检查项 | 为什么影响 AI 引用 |
|---|---|---|
| 1 | `robots.txt` 对 AI 爬虫的放行策略 | 被禁 ⇒ 引擎根本读不到你 |
| 2 | `llms.txt` 是否存在且结构正确 | 显式告诉 LLM 你是谁、哪页最权威 |
| 3 | JSON-LD 结构化数据（Organization / Product / FAQ） | 实体消歧，AI 才知道「你＝这个实体」 |
| 4 | `canonical` 与重复内容 | 多 URL 抢同一实体 ⇒ 引用被稀释 |
| 5 | 标题/H1 是否含可被引用的判断句 | 纯营销标题无法成为答案 |
| 6 | 可引用答案块（Q&A / 定义 / 数字） | AI 偏爱可直接摘录的段落 |
| 7 | 实体口径一致性（品牌名/写法/联系方式） | 口径不一致 ⇒ 引擎不敢引用 |
| 8 | 页面可访问性（状态码 / 渲染方式） | 客户端渲染内容常抓不到 |
| 9 | sitemap + IndexNow 收录链路 | 没收录 ⇒ 不进检索池 |
| 10 | 外链与提及（品牌被谁提到） | 第三方提及是可信度信号 |
| 11 | 结构化内容密度（表格/清单/FAQ） | 密度高 ⇒ 被摘录概率高 |
| 12 | 语义重复与竞品对标缺口 | 你缺的正是对手被引用的内容 |

## 公开报告库（样例）

👉 https://956231studio.com/audit/

---
*本仓库仅收录方法论与免费工具链接，由 956231studio 维护 · 联系：956231@qq.com*

---

Maintained by [956231 Studio](https://956231studio.com/) — practical packs for sellers and engineers, built and tested in production: [browse all packs](https://956231studio.com/packs/).
