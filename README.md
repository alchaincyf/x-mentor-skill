<div align="center">

# X导师.skill

<p align="center">
  <img src="assets/hero.gif" alt="x-mentor-skill Hero Animation" />
  <br/>
  <sub>动画由 <a href="https://github.com/alchaincyf/huashu-design">huashu-design</a> skill 制作</sub>
</p>

> 用自己账号的数据校正写法，让真实经历与可复用价值成为内容的核心。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安装)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**女娲的第一个「非人类」作品。不是蒸馏一个人，是蒸馏一个领域。**

<br>

基于 Nicolas Cole、Dickie Bush、Sahil Bloom、Justin Welsh、Dan Koe、Alex Hormozi<br>
六位创作者的方法论 + Tibo的实战复盘 + X平台一手资料，<br>
提炼 6 个核心心智模型、10 条决策启发式、完整的选题-写作-增长操作手册。

[使用示例](#使用示例) · [安装](#安装) · [本次更新](#2026-10-11更新) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 2026-10-11更新

将[Tibo的这次内容复盘](https://x.com/tibo_maker/status/2109214987038216210)纳入核心指南：以自己的数据修正写作习惯，重视完整表达、真实代价、可复用指南、个人经历与持续投入。作者个案和平台事实分别标记，不直接照搬英文市场结果。

- 取消120—130字符、外链必须进回复、默认60%英文、固定Thread长度等硬限制。
- 不再把算法预测概率的权重理解成「一个回复等于多少赞」。
- 30分钟低表现不自动删帖重发；默认按24小时、72小时观察，再测试一个变量。
- 账号诊断区分主帖、回复、原生Article与外链，区分曝光、归因关注、净增粉和使用行为。
- 增加经验回流与失效纠错；花叔表达范例是可选的个人风格参考，不是所有用户的人设。

本次进行了独立规则试跑与统计复核，修复了参考文件中的冲突。它们验证规则一致性与计算口径，不代表已经通过运营实验验证涨粉效果。账号后台原始数据、私有策略文件及本地报告不包含在仓库中；保留公开化的迁移示例与表达范例。

## 使用示例

「我想写800字中文项目复盘，正文放开源地址。」

→ 先核实真实结果与经历，按内容需要讲完整，把链接放在方便使用的位置，不强压成短帖。

「发了30分钟不火，要删了重发吗？」

→ 不把30分钟当生死线；记录24/72小时表现，检查开头承诺与正文交付，有新的价值再调整。

「分析我的X账号，给出下个月怎么发。」

→ 使用获授权的后台或导出数据，报告样本、时间窗、统计口径和缺失项，再给具体动作与验证办法，不保证增长。

---

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令（推荐，跨 runtime 自动检测）

```bash
npx skills add alchaincyf/x-mentor-skill
```

通用 CLI 安装器（[vercel-labs/skills](https://github.com/vercel-labs/skills)，支持 55+ runtime）会自动识别当前 runtime 并把 skill 放到正确目录。需要指定 runtime 时加 `-a claude-code` / `-a codex` / `-a cursor` / `-a openclaw` 等参数。

### 方式二：手动安装

<details>
<summary>展开查看各 runtime 的 skills 目录</summary>

| Runtime | 安装路径 |
|---|---|
| Claude Code | `~/.claude/skills/x-mentor-skill/` |
| Codex CLI | `~/.codex/skills/x-mentor-skill/` |
| Cursor | `~/.cursor/skills/x-mentor-skill/` |
| OpenClaw | `~/.openclaw/workspace/skills/x-mentor-skill/` |
| Hermes Agent | 跑该 runtime 的 install 脚本或 clone 到其 skills 目录 |

```bash
git clone https://github.com/alchaincyf/x-mentor-skill <对应路径>
```

</details>

### 方式三：作为参考资料使用

即使 runtime 不支持 Agent Skills 自动加载，你也可以把 `SKILL.md` 的内容粘贴进对话——它本质就是一份 markdown + YAML frontmatter。

### 使用

装好后，告诉你的 agent：「帮我写条推文」「X策略」「推特怎么涨粉」「帮我审阅这条tweet」「分析我的X账号」即可激活。

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
| 注意力工程 | 前两行说明价值，正文兑现承诺 | Cole + Hormozi(Value Equation) |
| 品类创造 | 不找赛道挤进去，创造只有你的品类 | Cole(Snow Leopard) + Koe(Niche of One) |
| 价值前置 | 把秘密免费给出去，卖执行 | Hormozi + Welsh + Sahil |
| 公开建造 | 把过程变成内容，观众变成利益相关者 | levelsio(Build in Public) + swyx(Learn in Public) |
| 系统化复利 | 用模板替代灵感，让产出可预测 | Welsh(Content OS) + Koe(2 Hour Writer) |

### 核心准则与平台事实

具体规则见[SKILL.md](SKILL.md)、[Tibo核心参考](references/tibo_core_principles.md)和[平台机制](references/algorithm-niche.md)。

X官方说明排序权重作用于预测概率，并非原始互动次数，因此不能将回复兑换成点赞。早期调研文件保留供追溯，不作当前算法事实；未核实的时段、频率与语言比例均需本账号验证。

---

## 调研来源

### 操作层references

| 文件 | 内容 | 行数 |
|------|------|------|
| `references/tibo_core_principles.md` | Tibo核心准则与迁移边界 | 36 |
| `references/huashu_x_expression_examples.md` | 花叔中文表达校准（可选） | 57 |
| `references/writing-workshop.md` | 短推文/Hook/Thread写法/选题系统 | 111 |
| `references/algorithm-niche.md` | X算法速查 + AI赛道专精 | 46 |
| `references/growth-monetization.md` | 增长引擎 + 变现 + 流派对比 | 92 |
| `references/quality-analytics.md` | 质量清单 + 反模式 + 复盘 + 报告模板 | 46 |
| `references/mental-models-heuristics.md` | 6个心智模型 + 10条启发式 | 221 |

### 调研层research（2026年4月历史资料，当前规则以SKILL.md为准）

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
6. **auto-optimizer迭代**：用8维度rubric评分，hill-climbing优化到88分

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
├── SKILL.md                              # 核心准则、场景流程与经验回流
├── references/
│   ├── tibo_core_principles.md           # 核心准则与迁移边界
│   ├── huashu_x_expression_examples.md   # 可选的花叔表达范例
│   ├── writing-workshop.md               # 写作工坊（按需加载）
│   ├── algorithm-niche.md                # 算法+AI赛道（按需加载）
│   ├── growth-monetization.md            # 增长+变现（按需加载）
│   ├── quality-analytics.md              # 质量+复盘+报告模板（按需加载）
│   ├── mental-models-heuristics.md       # 心智模型+启发式（按需加载）
│   └── research/                         # 6个调研文件（2475行，追溯来源时读取）
├── user-data/                            # 用户诊断数据（自动生成）
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

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*Your next $10K/hr mentor doesn't need to be human.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
