# Serenity 卡点投资分析技能

[![skills.sh](https://skills.sh/b/w-y-p/serenity-aleabitoreddit-skill)](https://skills.sh/w-y-p/serenity-aleabitoreddit-skill)

这是一个用于股票研究的 Codex 技能，用来复用 Serenity（@aleabitoreddit）的 AI 与半导体供应链卡点分析框架。

本仓库是研究与分析工具，不是投资建议、自动交易工具或信号服务。

### Serenity / @aleabitoreddit 是谁

Serenity（X: [@aleabitoreddit](https://x.com/aleabitoreddit)）是一位以 AI、半导体、光通信、CPO、材料和供应链瓶颈研究出圈的公开投资账号，也被许多投资者称为新晋 AI 股神。

她最突出的三点是：

- 2026 年投资回报率自述超过 45 倍，并因此快速出圈。
- 粉丝在 2026 年 5 月下旬快速增长到 40 万以上，并继续冲到 50 万级别。
- 长期免费分享研究、推理过程和投资想法，强调让散户也能看到高质量供应链研究。

她的核心方法不是追逐最显眼的 AI 龙头，而是沿着超大规模云厂商资本开支、ASIC/GPU/TPU、光通信、激光器、衬底、外延片、原材料和设备一路向上游追踪，寻找“小市值、低关注、但下游无法绕开的物理卡点”。

### 公开成就与影响力

以下数字用于描述公开影响力和研究背景：

- 2026-05-26，她在 X 上自述 `YTD: 4502.45%`，约等于 45 倍年内收益：[`2059292099728859430`](https://x.com/aleabitoreddit/status/2059292099728859430)。
- 2026-05-27 至 2026-05-30，她连续自述粉丝从 40 万增长到 50 万，并在 2026-05-28 自述约 4 万订阅者：[`2059479203746296219`](https://x.com/aleabitoreddit/status/2059479203746296219)、[`2059989579919401449`](https://x.com/aleabitoreddit/status/2059989579919401449)、[`2060628856445501924`](https://x.com/aleabitoreddit/status/2060628856445501924)。
- PANews / RootData 相关文章将其包装为“两年 225 倍 / 22,561.99%”的投资故事：[PANews 中文文章](https://www.panewslab.com/zh/articles/019e674b-724f-736c-8077-b2221cf24e39)。
- ChainCatcher 的方法论文章总结了她的 AI 卡脖子投资框架，包括需求确认、供给稀缺、低关注、价值捕获和催化剂：[ChainCatcher 文章](https://www.chaincatcher.com/en/article/2268235)。
- SemiconStocks 的 Serenity Tracker 将她的 AI 光子与 CPO 框架整理为多个供应链层级：[Serenity Tracker](https://semiconstocks.com/)。
- 本技能的初始研究语料恢复了 1,965 条公开/镜像推文，并参考了约 5,582 条推文语料和 4 篇 X 长文进行补充蒸馏。

### 这个技能做什么

`serenity-chokepoint-investing` 将 Serenity 的公开研究风格蒸馏成可复用的股票分析流程：

- 供应链卡点识别：从下游 AI 资本开支追踪到上游物理瓶颈。
- 多跳物料清单与开源情报映射：区分衬底、外延片、晶圆代工、激光器、光模块、封装、系统集成商等不同环节。
- 财务翻译：把瓶颈逻辑转成收入、利润率、现金流、融资和稀释场景。
- 催化剂与失效条件：跟踪财报、客户认证、政府补贴、上市场所提升、指数纳入、空头仓位、宏观冲击等。
- 风险审查：GAAP 利润率、ATM 增发、可转债、认股权证、客户集中、弱交易对手、过度社交反身性、期权与隐含波动率风险。
- 案例模板：AXTI、SIVE、SOI、AAOI/LITE/COHR、NBIS、欧洲光子产业链和新型云计算基础设施等模式。

### 如何使用

推荐通过 skills.sh 安装：

```bash
npx skills add w-y-p/serenity-aleabitoreddit-skill
```

也可以把仓库克隆到 Codex 技能目录：

```bash
git clone https://github.com/W-Y-P/Serenity-aleabitoreddit-skill.git ~/.codex/skills/serenity-chokepoint-investing
```

在 Codex 中显式调用：

```text
使用 $serenity-chokepoint-investing 分析 AXTI 是否是 AI 光通信 InP 衬底卡点。
```

推荐提问方式：

- “用 Serenity 框架分析这个股票代码的供应链位置、证据质量、财务转化、催化剂和失效条件。”
- “判断这家公司是真卡点、伪 AI 叙事，还是已经被市场充分定价。”
- “按 Serenity 风格审查这个投资组合里哪些名字有供应链卡点、稀释、客户集中或估值风险。”
- “使用 $serenity-chokepoint-investing 在 A 股中分析并推荐符合 AI 供应链卡点框架的股票候选，说明推荐逻辑、证据质量、催化剂和主要风险。”

### 文件结构

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── achievements_and_sources.md
    ├── case_patterns.md
    ├── maintenance.md
    ├── serenity_framework.md
    └── source_notes.md
```

### 重要免责声明

Serenity 的收益率、粉丝数、持仓、订阅数和案例回报多为自述、镜像观测或媒体报道。本技能只把这些内容当作研究背景和影响力变量。每个股票结论都需要用公司公告、财报、电话会纪要、客户披露、技术文档和当前市场数据重新验证。

## English

[![skills.sh](https://skills.sh/b/w-y-p/serenity-aleabitoreddit-skill)](https://skills.sh/w-y-p/serenity-aleabitoreddit-skill)

### Who Is Serenity / @aleabitoreddit?

Serenity ([@aleabitoreddit](https://x.com/aleabitoreddit) on X) is a public investor and AI/semiconductor supply-chain researcher known for focusing on physical bottlenecks in AI infrastructure. Many followers frame her as an emerging AI-stock star. Her public profile grew rapidly after self-reported 2026 returns above 45x, and her work is especially known for sharing detailed research and reasoning for free.

Her style is to look past the obvious AI winners and trace the supply chain upstream from hyperscaler capex to ASICs/GPUs/TPUs, optics, lasers, substrates, epiwafers, raw materials, and specialized tools.

The central question is: which small, underfollowed physical node can block or tax a much larger downstream buildout?

### Public Achievements And Influence

The following summarize public influence and research context:

- On 2026-05-26, Serenity self-reported `YTD: 4502.45%`, roughly a 45x year-to-date return if interpreted literally: [`2059292099728859430`](https://x.com/aleabitoreddit/status/2059292099728859430).
- From 2026-05-27 to 2026-05-30, she self-reported follower growth from 400k to 500k, and about 40k subscribers on 2026-05-28: [`2059479203746296219`](https://x.com/aleabitoreddit/status/2059479203746296219), [`2059989579919401449`](https://x.com/aleabitoreddit/status/2059989579919401449), [`2060628856445501924`](https://x.com/aleabitoreddit/status/2060628856445501924).
- PANews / RootData coverage framed her story as a 2-year 225x / 22,561.99% return narrative: [PANews Chinese article](https://www.panewslab.com/zh/articles/019e674b-724f-736c-8077-b2221cf24e39).
- ChainCatcher summarized her AI bottleneck method around confirmed demand, limited supply, low attention, value capture, and catalysts: [ChainCatcher article](https://www.chaincatcher.com/en/article/2268235).
- SemiconStocks maps many of her public AI photonics / CPO ideas by supply-chain layer: [Serenity Tracker](https://semiconstocks.com/).
- The original research pass behind this skill recovered 1,965 public or mirrored posts. It also draws on about 5,582 tweets and 4 X Articles as supplemental distillation material.

### What This Skill Does

`serenity-chokepoint-investing` turns Serenity's public research style into a reusable stock-analysis workflow:

- Supply-chain chokepoint detection from downstream AI capex to upstream physical constraints.
- Multi-hop BOM / OSINT mapping that separates substrate, epiwafer, foundry, laser, transceiver, module, package, and system-integrator roles.
- Financial translation into revenue, margin, cash flow, financing, and dilution scenarios.
- Catalyst and invalidation tracking across earnings, customer qualification, government funding, uplisting, index inclusion, short interest, macro shocks, and passive flows.
- Risk review across GAAP margin quality, ATM/convert/warrant overhang, customer concentration, weak counterparties, reflexive social attention, and options/IV risk.
- Case-pattern templates for AXTI, SIVE, SOI, AAOI/LITE/COHR, NBIS, European photonics names, and neocloud infrastructure.

### How To Use

Install through skills.sh:

```bash
npx skills add w-y-p/serenity-aleabitoreddit-skill
```

You can also clone this repository into your Codex skills directory:

```bash
git clone https://github.com/W-Y-P/Serenity-aleabitoreddit-skill.git ~/.codex/skills/serenity-chokepoint-investing
```

Invoke it explicitly in Codex:

```text
Use $serenity-chokepoint-investing to analyze SIVE as an AI CPO laser chokepoint.
```

Example prompts:

- “Use the Serenity framework to analyze this ticker's supply-chain role, evidence quality, financial translation, catalysts, and invalidation points.”
- “Decide whether this company is a real chokepoint, a loose AI narrative, or already fully priced.”
- “Review this portfolio through Serenity's lens and flag chokepoints, dilution risk, customer concentration, and valuation risk.”
- “Use $serenity-chokepoint-investing to analyze and recommend A-share stock candidates that fit the AI supply-chain chokepoint framework, including thesis logic, evidence quality, catalysts, and key risks.”

### Important Disclaimer

Serenity's returns, follower counts, subscribers, holdings, and case outcomes are mostly self-reported, mirror-observed, or media-reported. This skill treats them as context and reflexivity signals. Every stock thesis should be revalidated with filings, transcripts, company releases, customer disclosures, technical documents, and current market data.
