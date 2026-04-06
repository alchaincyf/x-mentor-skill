<div align="center">

# X导师.skill

> *「格式化是你能对写作做的最简单的10倍提升。」——Nicolas Cole*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**女娲的第一个「非人类」作品。不是蒸馏一个人，是蒸馏一个领域。**

<br>

基于 Nicolas Cole、Dickie Bush、Sahil Bloom、Justin Welsh、Dan Koe、Alex Hormozi<br>
六位年收入百万美元级X创作者的方法论 + X开源算法精确权重数据，<br>
提炼 6 个核心心智模型、10 条决策启发式、完整的选题-写作-增长操作手册。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 工作逻辑

![X导师.skill 路由逻辑](工作逻辑.png)

---

## 效果示例

### 写推文：生成3版Hook，标注公式来源

```
用户      ❯ 帮我写一条推文，关于我用Claude Code做了一个AI编程助手

X导师     ❯ 先确认：短推文 or Thread？目标受众？

用户      ❯ 短推文，给AI开发者看

X导师     ❯ 3个Hook版本：

            版本A（好奇缺口 + 可信度锚点）：
            「我用Claude Code做了一个AI编程助手。
            48小时，零框架，纯vibe coding。
            最意外的不是它能跑——是它比我手写的版本快3倍。」

            版本B（Value Equation：高结果/低effort）：
            「不会写代码？没关系。
            我刚用Claude Code在2天内做了一个AI编程助手。
            整个过程没写一行代码。这是我的完整过程：」

            版本C（争议观点 + 具体数据）：
            「大多数AI编程助手的评测都是Demo级别的。
            我用Claude Code做了一个真正上线的版本。
            区别在哪？30个edge cases和一个愿意debug到凌晨3点的AI。」

            推荐版本A，因为有具体数字(48h/3倍)和悬念。
            建议发布时间：工作日上午9-11点。
            ⚠️ 不要放外链，如需要放第一条回复里。
```

### 审阅Hook：诊断问题 + 给改写版

```
用户      ❯ 帮我看看这条：I tested 5 AI coding tools. Here's what I found.

X导师     ❯ Hook评分：3/10

            问题诊断：
            ❌ 零好奇缺口——没有悬念，读者不需要点进来
            ❌ 无可信度锚点——谁都能说"I tested"
            ❌ 无具体收益——"what I found"太模糊

            改写版：
            「I mass-tested 5 AI coding tools on the same project
            (a full-stack app in 48 hours).
            One saved me 12 hours. The others were useless.
            A thread:」

            改了什么：加了具体场景(full-stack app)、时间锚点(48h)、
            悬念(哪个？)、可信度(实测数据)
```

### 诊断增长瓶颈

```
用户      ❯ 我500粉丝，最近涨不动了

X导师     ❯ 500粉 → 0-1K冷启动阶段。先确认：开了Premium吗？

用户      ❯ 没有

X导师     ❯ 找到瓶颈了。

            没有Premium = TweepCred从-128起步。
            正常分发门槛是+17，你离这个门槛差145分。
            Premium订阅即时+100，这是你现在ROI最高的投资。

            开了Premium之后的每周行动计划：
            1. 每天发2-3条短推文（验证哪些话题有共鸣）
            2. 每天在5-10个AI大号评论区留高质量回复
               （200-400字，不是"好帖子"）
            3. DM 3个同量级创作者建立互助
            4. 不急着写Thread，先找到你的高ER话题

            预期：日均增粉5-10，4-8周到1K。
```

---

## 安装

```bash
npx skills add alchaincyf/x-mentor-skill
```

安装后，说「帮我写条推文」「X策略」「推特怎么涨粉」「帮我审阅这条tweet」即可激活。

---

## 蒸馏了什么

### 与人物Skill的区别

| 维度 | 人物Skill（如乔布斯.skill） | 主题Skill（X导师.skill） |
|------|---------------------------|------------------------|
| 蒸馏对象 | 一个人的思维方式 | 一个领域的方法论 |
| 信息来源 | 围绕一个人的6维度调研 | 6位顶级从业者 + 平台算法数据 |
| 输出风格 | 模拟该人语气回答 | 中性专业，给操作手册 |
| 核心价值 | 用别人的眼睛看你的问题 | 给你可直接执行的行动计划 |

### 6个核心心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| 精益验证飞轮 | 先发tweet验证，数据好再扩展 | Cole/Bush + Sahil + Hormozi + Welsh |
| 注意力工程 | 前2行决定生死，hook可以被工程化 | Cole + Hormozi(Value Equation) + 算法验证 |
| 品类创造 | 不找赛道挤进去，创造只有你的品类 | Cole(Snow Leopard) + Koe(Niche of One) |
| 价值前置 | 把秘密免费给出去，卖执行 | Hormozi + Welsh + Sahil |
| 公开建造 | 把过程变成内容，观众变成利益相关者 | levelsio(Build in Public) + swyx(Learn in Public) |
| 系统化复利 | 用模板替代灵感，让产出可预测 | Welsh(Content OS) + Koe(2 Hour Writer) |

### 10条决策启发式

1. **先发推文再写长文** — tweet是想法炼油厂
2. **Hook占50%创作时间** — 写10-15个版本选最好的
3. **对话碾压一切** — 对话回复=150个点赞（X开源代码）
4. **1/3/1节奏** — 一句hook+三句展开+一句过渡
5. **超级碗响应** — 新模型发布=AI赛道的超级碗，0-1h内响应
6. **拥有你的受众** — 算法会变，newsletter不会
7. **4A选题矩阵** — 一个话题×4角度=无限选题
8. **给出秘密卖执行** — 99%的人不会自己做
9. **模板大于灵感** — Cole用7种模板写了200+条Thread
10. **评论区是金矿** — 一条回复获得6700次曝光

### X算法关键数据（2026年4月，开源代码确认）

| 互动类型 | 算法权重 | 来源 |
|----------|---------|------|
| 对话回复（你的回复被作者回复） | **150x** | 开源代码 |
| 普通回复 | **27x** | 开源代码 |
| 停留时间（>2分钟） | **20x** | 开源代码 |
| 转发 | **2x** | 开源代码 |
| 点赞 | **1x（基准）** | 开源代码 |

⚠️ 外部链接降触达30-50%，非Premium用户链接帖中位互动为零。

---

## 调研来源

6个调研文件，共2475行，全部在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-writing-methods.md` | Nicolas Cole / Dickie Bush / Ship 30 for 30 写作方法论 | 503 |
| `02-growth-engines.md` | Sahil Bloom / Justin Welsh 增长引擎与系统化运营 | 386 |
| `03-content-brand.md` | Dan Koe / Alex Hormozi 内容品牌与价值前置 | 398 |
| `04-platform-mechanics.md` | X算法机制、开源代码分析、TweepCred | 415 |
| `05-ai-tech-niche.md` | AI/科技赛道策略、Build in Public、中国开发者出海 | 404 |
| `06-cases-antipatterns.md` | 成功案例拆解与常见失败模式 | 369 |

### 核心人物

- **Nicolas Cole** — Ship 30 for 30联创，累计1亿+在线阅读量，Lean Writing/4A Framework/Category Design
- **Dickie Bush** — 30个月0→326K粉丝，Atomic Essay/75-25法则
- **Sahil Bloom** — 不到2年0→190万粉丝，内容飞轮/费曼式写作
- **Justin Welsh** — solopreneur标杆，$12M年收入90%利润率，Content OS/7步增长法
- **Dan Koe** — One-Person Business/Niche of One/2 Hour Writer
- **Alex Hormozi** — 零广告费6个月100万粉丝，Hook-Retain-Reward/Value Equation

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 生成——但这次不是蒸馏一个人，是蒸馏一个领域。

女娲在处理「主题Skill」时的变体流程：
1. **确认蒸馏对象**：不是一个人名，而是一个主题（X运营）+ 3-5个核心人物
2. **6路并行调研**：每路Agent负责不同维度（写作方法论/增长引擎/内容品牌/平台算法/AI赛道/案例反模式）
3. **交叉验证提炼**：从6个人的方法论中找共识框架和分歧点
4. **构建操作手册**：不模拟任何人的语气，而是给出可直接执行的步骤
5. **双Agent验证**：独立Agent做质量测试（已知测试+边缘测试+风格测试）
6. **auto-optimizer迭代**：用8维度rubric评分，hill-climbing优化到90分

想蒸馏其他主题？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

说「造一个关于XXX的skill」就行。人物和主题都支持。

---

## 仓库结构

```
x-mentor-skill/
├── README.md
├── SKILL.md                              # 可直接安装使用（769行）
├── references/
│   └── research/                         # 6个调研文件（2475行）
│       ├── 01-writing-methods.md         # Cole/Bush/Ship30 方法论
│       ├── 02-growth-engines.md          # Sahil/Welsh 增长引擎
│       ├── 03-content-brand.md           # Koe/Hormozi 品牌策略
│       ├── 04-platform-mechanics.md      # X算法机制+开源代码
│       ├── 05-ai-tech-niche.md           # AI赛道专精策略
│       └── 06-cases-antipatterns.md      # 案例拆解+失败模式
└── examples/
    └── account-diagnosis-demo.md         # 真实X账号诊断案例
```

---

## 更多.skill

女娲已蒸馏的作品，每个都可独立安装：

### 人物Skill

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

### 主题Skill

| 主题 | 领域 | 安装 |
|------|------|------|
| **X导师.skill** | X/Twitter运营全栈 | `npx skills add alchaincyf/x-mentor-skill` |

想蒸馏更多？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字或主题即可。

---

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---

<div align="center">

*Your next $10K/hr mentor doesn't need to be human.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
