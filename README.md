<img width="2048" height="2048" alt="image" src="https://github.com/user-attachments/assets/59b7b430-8278-41a9-9b4d-05cef371ddc2" /><img width="2048" height="2048" alt="image" src="https://github.com/user-attachments/assets/65373b66-06b9-49f2-b38f-f313db61057b" /># TestFirst · 测试优先
 
> 追觅俞浩的极小试错决策系统
>
> **"与其洞察，不如测试。"** —— 俞浩，追觅科技创始人
 
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Agent Skills](https://img.shields.io/badge/Agent-Skills-purple)](https://github.com/anthropics/skills)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-compatible-orange)](https://github.com/openclaw)
[![Hermes](https://img.shields.io/badge/Hermes-compatible-green)](https://github.com/nous-research/hermes)
[![Claude Projects](https://img.shields.io/badge/Claude-Projects-blueviolet)](https://claude.ai)
 
---
 
**不是俞浩的人物介绍。不是商业分析报告。**
 
是他8年年均100%增长背后的决策逻辑，拆解成你今天就能用的**可运行框架**。
 
---
 
## 效果示例
 
### 问1：我有个新产品方向，做了很多用户调研，但还是不确定值不值得做。
 
```
俞浩视角 >
 
停。先问你一个问题。
 
你调研了多少人？20个？50个？
他们有没有真的付钱给你？
 
没有付钱，就不算验证。
用户说"我会买"——这句话一分不值。
用户掏出钱包——这才是数据。
 
我们做割草机的时候，行业都在往
499美元卷。没有人做用户调研说
"用户愿意为激光雷达多付1000美元"。
我们直接上市，1999美元，卖爆了。
 
不是因为我们敢赌。
是因为我们找到了用户最核心的那个痛——
边界识别总是出错，剪坏了草坪。
解决了这个，价格不是问题。
 
你现在做的产品，用户最频繁抱怨的
那一个问题是什么？
不是前三个。是那一个。
 
找到了，用最小成本做一个只解决
这一个问题的东西，收钱，看有多少人付。
这才是验证。
```
 
> **激活的心智模型：极小试错半径** — 真实购买行为是唯一有效的验证，口头意愿不算数据。在投入大量资源之前，先用最小成本拿到真实反馈。
 
---
 
### 问2：我想做自媒体，但不知道做什么内容，发了几条没什么反响就放弃了。
 
```
俞浩视角 >
 
你犯了一个大错误。
 
你在等灵感，然后再发。
这个逻辑是反的。
 
我五一假期单日发了117条视频。
你知道我发之前知道哪条会火吗？
不知道。完全不知道。
 
我认为会火的反而没火。
我认为平平无奇的反而爆了。
 
这不是因为我判断力差。
是因为平台算法是个黑盒，
任何人的"洞察"都没用。
 
唯一有用的是：发足够多，
让数据告诉你规律。
 
发3条得出结论——这叫抽样误差，
不叫验证。
 
发够30条，看哪类完播率高。
发够100条，你的SOP就出来了。
 
然后你才知道"做什么内容"。
不是想出来的，是测出来的。
```
 
> **激活的心智模型：不用洞察，用测试** — 样本量不够的判断不是判断，是猜测。先有足够的实验，再提炼规律。
 
---
 
### 问3：我们做的是ToB产品，客户说很好但就是不签单，怎么回事？
 
```
俞浩视角 >
 
我告诉你答案，但你可能不想听。
 
"客户说好"——这不是信号。
这是礼貌。
 
中国商业文化里，说"好"是最低成本
的结束对话方式。它不代表任何意思。
 
唯一代表意思的，是他们花了什么：
钱、时间、或者内部政治资本。
 
问你一个问题：你们产品免费试用吗？
免费试用了多久还没转付费？
 
三个月免费试用还没转化，
说明不是产品问题，是价值问题——
你解决的那个痛，没痛到他们
愿意走采购流程的程度。
 
缩小范围。找那一个客户，
那个会在内部为你们吵架、
帮你们推动采购的人。
他为什么这么做？他解决了什么
让他自己难堪的问题？
 
这才是你真正的价值。
不是PPT上写的那些。
```
 
> **激活的心智模型：N+1定位** — 真正的产品价值是解决了某个人某个具体的痛，而不是宽泛的"提升效率"。找到那个人，找到那个痛。
 
---
 
**这不是把俞浩的语录喂给ChatGPT。**
 
每段回应都在运用他的具体决策框架——「极小试错半径」「N+1创新」「不用洞察用测试」。
 
**不是模仿他说话，是用他的思维框架分析你的问题。**
 
---
 
## 安装
 
本Skill基于开放的 [Agent Skills](https://github.com/anthropics/skills) 协议，支持 Claude Code、OpenClaw、Hermes Agent 等主流 runtime。
 
### 方式一：一行命令（推荐）
 
```bash
npx skills add [你的GitHub用户名]/testfirst-yuhao-perspective
```
 
### 方式二：手动放入
 
| Runtime | 目录 |
|---------|------|
| Claude Code | `.claude/skills/` |
| OpenClaw | `.openclaw/skills/` |
| Hermes Agent | `.hermes/skills/` |
 
### 方式三：Claude Projects（无需代码）
 
1. 打开 Claude.ai → Projects → 新建项目
2. 把 `SKILL.md` 全部内容粘贴到 Project Instructions
3. 开始使用
### 方式四：任何AI工具
 
把 `SKILL.md` 内容粘贴到对话开头作为 System Prompt。
 
---
 
## 使用
 
装好之后，直接说：
 
```
用俞浩视角分析这个产品方向：[你的想法]
 
帮我用N+1方法找这个品类的切入点
 
用极小试错逻辑，帮我设计一个最小验证方案
 
俞浩会怎么看这个定价策略
```
 
---
 
## 蒸馏了什么
 
### 5个心智模型
 
| 模型 | 一句话 | 真实案例 |
|------|--------|----------|
| **极小试错半径** | 最小成本验证，不在验证前押注 | 割草机$1999定价直接上市，而非先做调研 |
| **N+1创新方法论** | 成熟的N + 你的技术长板解决那一个痛 | 车用激光雷达 → 割草机边界识别，反卷爆款 |
| **不用洞察用测试** | 口头意愿不算数据，购买行为才算 | 117条视频/日，让数据告诉你什么内容会火 |
| **左右模型** | 经营能力（左）和社会资源（右）两边都要硬 | 主业持续盈利支撑新业务试错，区别于乐视 |
| **工程师修正系统** | CEO的错误没人修正，工程师的错误被系统修正 | 把直觉变成可验证的假设，让市场来修正 |
 
### 6问决策检查表
 
做任何重要决策前，先问自己：
 
- [ ] 我是在凭洞察，还是有真实购买数据支撑？
- [ ] 我解决的是用户最核心的那一个问题，还是大而全？
- [ ] 这个+1，我有没有别人短期内难以复制的差异化能力？
- [ ] 验证方式是真实购买行为，还是用户口头反馈？
- [ ] 我的主营业务能支撑这个新方向的试错成本吗？
- [ ] 如果这个决策是错的，代价足够小、可以修正吗？
### 3套完整SOP
 
1. **N+1三步SOP** — 找痛点 → 判断+1 → 极小试验，每步有具体执行动作
2. **自媒体增长SOP** — 俞浩117条视频的实验逻辑，拆解成可复制步骤
3. **定价验证SOP** — 怎么在不做大规模调研的前提下，找到用户真实愿意付的价格
完整内容见 [`SKILL.md`](./SKILL.md)。
 
---
 
## 真实案例验证
 
每个框架都有追觅的实战数据支撑：
 
| 框架 | 案例 | 结果 |
|------|------|------|
| N+1创新 | 车用激光雷达应用到割草机 | $1999 vs 竞品$499，卖爆。2026年Q1同比增长174% |
| 极小试错 | 高频社交媒体内容测试算法 | 单日117条 → 找到规律 → 量化复制到2.2万员工 |
| 技术复用 | 高速马达 → 吸尘器 → 割草机 → 汽车 → 机器人 | 连续8年年均100%+增长 |
| 左右模型 | 主业盈利支撑新业务试错 | 8年累计盈利 — 区别于乐视崩盘路径 |
 
---
 
## 调研来源
 
| 来源 | 内容类型 |
|------|----------|
| 界面新闻《揭秘追觅"宇宙"》 | 深度报道 |
| 虎嗅《俞浩激进扩张引争议》 | 深度报道 |
| 网易财经《N+1创新方法论》专访 | 一手采访 |
| 36氪 / 钛媒体 / DoNews | 专访报道 |
| B站俞浩访谈视频 | 原始视频 |
 
**数据截止：2026年5月**
 
**已排除：** 未经核实的二手传播内容
 
---
 
## 适用场景
 
✅ **早期创业者** — 资源有限，需要在验证前找到最小试错路径
 
✅ **产品经理** — 需要在上线前验证假设，而不是凭感觉做决策
 
✅ **自媒体创作者** — 需要系统化测试，而不是凭感觉发内容
 
✅ **硬件 / 消费品从业者** — N+1在有成熟竞品的赛道效果最好
 
❌ 纯软件 / 互联网产品（俞浩经验集中在硬件制造）
 
❌ 0→1颠覆式创新场景（N+1建立在成熟N的基础上）
 
---
 
## 仓库结构
 
```
testfirst-yuhao-perspective/
├── README.md          ← 你在看的这个（中文版）
├── README_EN.md       ← English version
├── SKILL.md           ← 直接放进AI工具使用
└── LICENSE
```
 
---
 
## 这个Skill是怎么做的
 
基于俞浩 **5篇以上深度专访** + **B站视频原始素材** + **多家财经媒体报道**，提炼核心决策模型，验证真实商业案例，写成可直接触发的 Skill 格式。
 
参考了花叔 [@AlchainHust](https://github.com/AlchainHust) 的女娲.skill框架规范。
 
---
 
## 如果对你有用
 
**点右上角 ⭐ Star — 这也是一种极小试错。**
 
发现它对你有价值，再决定深入使用。
 
---
 
## 相关文章
 
📖 [追觅俞浩刷屏全网，但他最值得学的不是百万亿目标](#) · `dehaze毋霾社` 公众号
 
---
 
## 关于作者
 
**dehaze毋霾社** — AI产品人，前HOK建筑师，美团 / 小鹏 / 某大厂机器人产品负责人。
 
**专注：** AI产品洞察 × 创业方法论 × 具身智能
 
| 平台 | 链接 |
|------|------|
| 📱 公众号 | 微信搜索「dehaze毋霾社」 |
| 💬 后台私信 | 有问题直接留言，有空必回 |
 
---
 
**MIT License** — 随便用，随便改，注明来源即可。

# TestFirst · Minimum Viable Bet
 
> The Decision System Behind Dreame's 8 Years of 100%+ Annual Growth
>
> **"Instead of insight, run a test."** — Yu Hao, Founder & CEO of Dreame Technology
 
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Agent Skills](https://img.shields.io/badge/Agent-Skills-purple)](https://github.com/anthropics/skills)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-compatible-orange)](https://github.com/openclaw)
[![Hermes](https://img.shields.io/badge/Hermes-compatible-green)](https://github.com/nous-research/hermes)
[![Claude Projects](https://img.shields.io/badge/Claude-Projects-blueviolet)](https://claude.ai)
 
---
 
**Not a biography. Not a business case study.**
 
The decision-making logic behind 8 consecutive years of 100%+ compound annual growth — broken down into a **runnable framework** you can use today.
 
[See it in action](#see-it-in-action) · [Install](#install) · [What's inside](#whats-inside) · [Sources](#sources)
 
---
 
## See it in action
 
### Q1: I've done a lot of user research on my new product idea, but I'm still not sure if it's worth building.
 
```
Yu Hao perspective >
 
Stop. Let me ask you one thing.
 
How many people did you interview? 20? 50?
Did any of them actually pay you money?
 
If they didn't pay, it's not validation.
"I would buy this" — that sentence is worth nothing.
Someone opening their wallet — that's data.
 
When we built our lawnmower robot, everyone in
the industry was racing to the bottom at $499.
Nobody did user research saying customers would
pay $1,000 more for LiDAR.
We just launched at $1,999. It sold out.
 
Not because we were gambling.
Because we found the one core pain —
boundary detection kept failing, ruining lawns.
Solve that, and price stops being an objection.
 
What's the one thing your users complain about
most? Not the top three. The one.
 
Find it. Build the smallest thing that solves
only that. Charge money. See who pays.
That's validation.
```
 
> **Mental model activated: Minimum Viable Bet** — Real purchase behavior is the only valid signal. Stated intent is not data. Get real feedback before committing significant resources.
 
---
 
### Q2: I want to build an audience online, but I posted a few times with no traction and gave up.
 
```
Yu Hao perspective >
 
You made one big mistake.
 
You waited for inspiration before posting.
That logic is backwards.
 
During China's Labor Day 2026, I posted
117 videos in a single day.
Did I know which ones would go viral?
No. Not at all.
 
The ones I thought would blow up — didn't.
The ones I thought were nothing — exploded.
 
This isn't because my judgment is bad.
It's because platform algorithms are a black box.
Nobody's "intuition" works on a black box.
 
The only thing that works: post enough,
and let data tell you the pattern.
 
3 posts and drawing conclusions — that's
sampling error, not validation.
 
Post 30. See which ones get watched to the end.
Post 100. Your SOP will emerge on its own.
 
Then you'll know what content to make.
Not because you thought it through —
because you tested your way to the answer.
```
 
> **Mental model activated: Test over insight** — Small sample conclusions aren't conclusions, they're guesses. You need enough experiments before you can extract a pattern.
 
---
 
### Q3: Our B2B product gets great feedback from customers, but they never sign.
 
```
Yu Hao perspective >
 
I'll tell you the answer. You might not like it.
 
"Customers say it's great" — that's not a signal.
That's politeness.
 
In business, saying "great" is the lowest-cost
way to end a conversation.
It means nothing.
 
The only thing that means something is
what they spend: money, time, or political
capital inside their organization.
 
Question: do you offer a free trial?
How long have they been using it for free
without converting to paid?
 
Three months of free usage with no conversion
means it's not a product problem.
It's a value problem —
the pain you're solving isn't painful enough
for them to navigate a procurement process.
 
Narrow your focus. Find the one customer
who would argue for you internally,
who would push your procurement through.
What embarrassing problem are you solving for them?
 
That's your real value.
Not what's written in your pitch deck.
```
 
> **Mental model activated: N+1 positioning** — Real product value means solving one specific person's specific pain. Find that person. Find that pain.
 
---
 
**This isn't Yu Hao's quotes fed into ChatGPT.**
 
Every response applies his specific decision frameworks — *Minimum Viable Bet*, *N+1 Innovation*, *Test over insight*.
 
**It doesn't imitate how he talks. It uses his thinking to analyze your problem.**
 
---
 
## Install
 
This Skill follows the open [Agent Skills](https://github.com/anthropics/skills) protocol, compatible with Claude Code, OpenClaw, Hermes Agent, and other major runtimes.
 
### Option 1: One command (recommended)
 
```bash
npx skills add [your-github-username]/testfirst-yuhao-perspective
```
 
### Option 2: Manual install
 
| Runtime | Directory |
|---------|-----------|
| Claude Code | `.claude/skills/` |
| OpenClaw | `.openclaw/skills/` |
| Hermes Agent | `.hermes/skills/` |
 
### Option 3: Claude Projects (no code needed)
 
1. Go to Claude.ai → Projects → Create new project
2. Paste the full content of `SKILL.md` into Project Instructions
3. Start using it
### Option 4: Any AI tool
 
Paste the contents of `SKILL.md` at the start of any conversation as a system prompt.
 
---
 
## Usage
 
Once installed, just say:
 
```
Use Yu Hao's perspective to analyze this product direction: [your idea]
 
Help me find the N+1 entry point for this category
 
Design a minimum viable test for this hypothesis
 
How would Yu Hao think about this pricing strategy
```
 
---
 
## What's Inside
 
### 5 Mental Models
 
| Model | One line | Real case |
|-------|----------|-----------|
| **Minimum Viable Bet** | Smallest cost to validate, no big bets before proof | Launched lawnmower at $1,999 directly — no pre-market research |
| **N+1 Innovation** | Mature N + your technical edge solving the one core pain | Automotive LiDAR → lawnmower boundary detection → outsold $499 competitors at $1,999 |
| **Test over insight** | Purchase behavior is data. Stated intent is not. | 117 videos/day — let data reveal what content works |
| **Left-Right Model** | Operational ability (left) and social resources (right) — you need both | Core business profitability funds new venture experiments |
| **Engineer's Correction System** | A CEO's mistakes go uncorrected. An engineer's get fixed by the system. | Turn intuition into testable hypotheses, let market correct direction |
 
### 6-Question Decision Checklist
 
Before any major decision, ask yourself:
 
- [ ] Am I acting on intuition, or do I have real purchase data?
- [ ] Am I solving the single most important pain, or trying to do everything?
- [ ] Does my +1 give me a real edge that competitors can't easily copy?
- [ ] Is my validation method real purchase behavior, or just user feedback?
- [ ] Can my core business support the cost of being wrong here?
- [ ] If this decision is wrong, is the cost small enough to recover from?
### 3 Complete SOPs
 
1. **N+1 Three-Step SOP** — Find the pain → Identify your +1 → Run minimum test. Specific actions for each step.
2. **Content Growth SOP** — The logic behind Yu Hao's 117-video experiment, broken into repeatable steps
3. **Pricing Validation SOP** — How to find what users will actually pay, without large-scale research
Full content in [`SKILL.md`](./SKILL.md).
 
---
 
## The Evidence
 
Every framework in this Skill is backed by Dreame's real outcomes:
 
| Framework | Case | Result |
|-----------|------|--------|
| N+1 Innovation | Applied automotive LiDAR to lawnmowers | $1,999 vs competitors at $499 — sold out. 174% YoY growth Q1 2026 |
| Minimum Viable Bet | High-frequency social posting to test algorithms | 117 videos/day → found patterns → scaled to 22,000 employees |
| Technology compounding | High-speed motor → vacuum → lawnmower → EV → robotics | 100%+ CAGR for 8 consecutive years |
| Left-Right Model | Core profitability funds new venture experiments | 8-year cumulative profit — contrasted with Leshi/LeEco collapse |
 
---
 
## Sources
 
| Source | Type |
|--------|------|
| Interface News — *Unveiling Dreame's "Universe"* | Long-form investigation |
| Huxiu — *Yu Hao's Aggressive Expansion* | Deep reporting |
| 163.com / NetEase Finance — *N+1 Interview* | First-hand interview |
| 36Kr / Titanium Media / DoNews | Interviews & reporting |
| Yu Hao video interviews on Bilibili | Original video |
 
**Data current as of:** May 2026
 
**Excluded:** unverified second-hand content
 
---
 
## Who This Is For
 
✅ **Early-stage founders** — Limited resources, can't afford big mistakes, need to validate before scaling
 
✅ **Product managers** — Need to test assumptions before shipping, not follow gut feeling
 
✅ **Content creators** — Need systematic testing, not guesswork about what will resonate
 
✅ **Hardware / consumer product builders** — N+1 works best in markets with mature existing products
 
❌ Pure software / internet products (Yu Hao's experience is in hardware manufacturing)
 
❌ True 0→1 category creation (N+1 requires a mature "N" to build on)
 
---
 
## Repository Structure
 
```
testfirst-yuhao-perspective/
├── README.md          ← Chinese version
├── README_EN.md       ← This file
├── SKILL.md           ← Load this into your AI tool
└── LICENSE
```
 
---
 
## How This Was Made
 
Based on **5+ deep-dive interviews** with Yu Hao, **Bilibili video content**, and **reporting from major Chinese financial media**. Core decision models extracted, validated against real business cases, and formatted as a triggerable Skill.
 
Inspired by the Nuwa.skill framework by [@AlchainHust](https://github.com/AlchainHust).
 
---
 
## If This Was Useful
 
**Hit ⭐ Star in the top right — that's also a minimum viable bet.**
 
See if it's valuable first, then decide whether to go deeper.
 
---
 
## Related
 
📖 [The article that inspired this Skill](#) · `dehaze毋霾社` on WeChat
 
---
 
## About the Author
 
**dehaze毋霾社** — AI product builder. Former architect (HOK), product roles at Meituan (drone delivery), Xpeng (overseas voice products), now leading robot interaction products at a major tech company.
 
**Focus:** AI product insights × startup methodology × embodied intelligence
 
| Platform | Link |
|----------|------|
| 📱 WeChat Official Account | Search「dehaze毋霾社」 |
| 💬 Direct message | Leave a comment — will reply when available |
 
---
 
**MIT License** — use freely, modify freely, attribution appreciated.
