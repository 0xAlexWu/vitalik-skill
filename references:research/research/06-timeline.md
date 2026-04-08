# Vitalik Buterin v2 时间线调研

> 维度 6：人物时间线、思想转折点、最近 12 个月动态。
>
> 调研时间：2026-04-07。
>
> 本文件只写时间线维度，不写最终 `SKILL.md`。信息源黑名单已遵守：未使用知乎、微信公众号、百度百科/百度知道。

## 0. 方法与来源分级

### 来源分级

- **一手 / 官方**：Vitalik 本人博客镜像、Ethereum.org、Ethereum Foundation blog、Ethereum Research。
- **近一手 / 二手转述**：Vitalik 公开 X 内容的可信转述；只有 Vitalik 账号直链、可验证截图或原文抓取才作为一手处理。
- **本地语料**：`local-vitalik_100_txt` 内 100 个编号 txt。该包是摘要学习笔记，不是逐字原文；适合做主题聚类与时间线索引，不适合做精确引文。
- **二手 / 媒体与学术**：The Guardian、Business Insider、Cointelegraph、TIME、SSRN 等，用于补充外部视角、社区争议与近期动态。
- **推断**：基于多来源重复模式对“思想转折”的归纳；不会写成 Vitalik 明说。

### 本地 100 txt 的纳入方式

本地包覆盖 85 篇 Vitalik 个人博客、10 篇 Ethereum Foundation blog、5 篇 Ethereum Research。最相关的时间线锚点包括：

- 早期协议与 PoS：`088_Slasher A Punitive Proof-of-Stake Algorithm.txt`、`090_The Evolution of Ethereum.txt`、`094_Scalability, Part 1 Building on Top.txt`、`095_Scalability, Part 2 Hypercubes.txt`
- DAO 与安全：`091_Onward from the Hard Fork.txt`、`092_Privacy on the Blockchain.txt`、`093_Thinking About Smart Contract Security.txt`
- 扩容与 L2：`004_Scaling Ethereum L1 and L2s in 2025 and beyond.txt`、`005_How do layer 2s really differ from execution sharding.txt`、`012_An Incomplete Guide to Rollups.txt`、`035_A short guide to blobs and proto-danksharding.txt`
- 治理与社会层：`010_The Most Important Scarce Resource is Legitimacy.txt`、`020_Moving beyond coin voting governance.txt`、`027_The future of institutions.txt`、`030_Control as a liability.txt`、`031_Balance of power and the social layer.txt`
- AI / 隐私 / 身份 / 开源：`022_Why I support privacy.txt`、`023_Why I support open source and copyleft.txt`、`025_Only open source can make AI aligned.txt`、`053_AI, humans and the edges of agency.txt`、`054_Against biometric identity maximalism.txt`

## 1. 核心时间线

| 时间 | 类型 | 节点 | 事实 / 解释 | 来源 |
|---|---|---|---|---|
| 1994 | 确定事实 | 出生于俄罗斯，后在加拿大长大 | Ethereum.org 记载 Buterin 1994 年出生于俄罗斯，在加拿大成长，并从小表现出数学天赋。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/ |
| 2011 | 确定事实 | 发现 Bitcoin | Ethereum.org 记载他在 2011 年发现 Bitcoin，并开始写相关文章。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/ |
| 2012 | 确定事实 | 共同创办 Bitcoin Magazine | 这使他从观察者进入加密社区的叙事生产与解释角色。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/ |
| 2013-11 | 确定事实 | 分享 Ethereum 白皮书 | Ethereum.org 记载他在 2013 年 11 月分享白皮书，提出可运行智能合约的区块链平台。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/；https://ethereum.org/whitepaper/ |
| 2014-01 | 确定事实 | 在北美 Bitcoin 会议公开宣布 Ethereum | 从“Bitcoin 可否更通用”进入公开项目阶段。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/ |
| 2014-01 | 确定事实 | Slasher / PoS 惩罚机制早期提案 | 早期就把 PoS、惩罚、硬件门槛和去中心化安全放入路线图。 | https://blog.ethereum.org/2014/01/15/slasher-a-punitive-proof-of-stake-algorithm；`088_Slasher A Punitive Proof-of-Stake Algorithm.txt` |
| 2014-05 | 确定事实 | DAO / DAC / DA 术语整理 | 说明他很早就把链上协议与组织设计相连。 | https://blog.ethereum.org/2014/05/06/daos-dacs-das-and-more-an-incomplete-terminology-guide；`089_DAOs, DACs, DAs and More An Incomplete Terminology Guide.txt` |
| 2014-07 至 2014-08 | 确定事实 | Ether sale | Ethereum.org 记载公开众筹筹集约 31,000 BTC，用于开发。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/；https://ethereum.org/ethereum-forks/ |
| 2014-09 | 确定事实 | 早期扩容系列 | 从早期开始，scaling 已被定义为架构与去中心化之间的系统权衡。 | https://blog.ethereum.org/2014/09/17/scalability-part-1-building-top；`094_Scalability, Part 1 Building on Top.txt` |
| 2014-11 | 确定事实 | 讨论 Bitcoin maximalism 与网络效应 | 早期就把货币、平台、网络效应与多链生态放到一起分析。 | https://blog.ethereum.org/2014/11/20/bitcoin-maximalism-currency-platform-network-effects；`087_On Bitcoin Maximalism, and Currency and Platform Network Effects.txt` |
| 2015-04 | 确定事实 | Olympic 测试网 | 主网上线前最后测试阶段。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/ |
| 2015-07-30 | 确定事实 | Ethereum 主网 / Frontier 启动 | Ethereum.org 记载主网于 2015-07-30 正式启动；技术史页将 Frontier 描述为面向技术用户的早期实现。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/；https://ethereum.org/ethereum-forks/ |
| 2015-09 | 确定事实 | The Evolution of Ethereum | 从单一协议构想扩展到 web3 栈、社区与工具链。 | https://blog.ethereum.org/2015/09/28/the-evolution-of-ethereum；`090_The Evolution of Ethereum.txt` |
| 2016-01 | 确定事实 | Privacy on the Blockchain | 隐私从边缘话题进入协议设计中心。 | https://blog.ethereum.org/2016/01/15/privacy-on-the-blockchain；`092_Privacy on the Blockchain.txt` |
| 2016-03-14 | 确定事实 | Homestead 升级 | Ethereum.org 将 Homestead 标为第一个计划升级，意味着以太坊进入更主流可用阶段。 | https://ethereum.org/zh/ethereum-history-founder-and-ownership/ |
| 2016-06 | 确定事实 | Thinking About Smart Contract Security | 安全观从“写对代码”扩展为分层、渐进、防御纵深。 | https://blog.ethereum.org/2016/06/19/thinking-smart-contract-security；`093_Thinking About Smart Contract Security.txt` |
| 2016-07 | 确定事实 | DAO hard fork / Onward from the Hard Fork | DAO 事件让社会层、合法性、分叉与软权力成为长期核心问题。 | https://blog.ethereum.org/2016/07/26/onward-from-the-hard-fork；`091_Onward from the Hard Fork.txt` |
| 2017 | 确定事实 | PoS FAQ、Sharding FAQ、governance 写作 | 这一阶段他持续把 PoS、分片与治理作为长期路线主轴。 | https://vitalikblog.w3eth.io/；本地 `073_CBC Casper and consensus intuition.txt`、`100_A model for stage 4...txt` |
| 2019 | 确定事实 | Control as Liability、Collusion、Hybrid L2 | 从单纯协议工程进一步转向权力、串谋、混合二层与机制设计。 | https://vitalikblog.w3eth.io/；`030_Control as a liability.txt`、`046_On collusion.txt` |
| 2020 | 确定事实 | A Philosophy of Blockchain Validation、Why Proof of Stake | 验证哲学、PoS 与协调问题成为成熟表达的一部分。 | https://vitalikblog.w3eth.io/；`013_A Philosophy of Blockchain Validation.txt` |
| 2021-01 | 确定事实 | An Incomplete Guide to Rollups | rollup-centric 路线图进入系统化阐述阶段。 | https://vitalikblog.w3eth.io/；`012_An Incomplete Guide to Rollups.txt` |
| 2021-03 | 确定事实 | Legitimacy | 将合法性定义为加密生态最稀缺的社会资源之一。 | https://vitalikblog.w3eth.io/general/2021/03/23/legitimacy.html；`010_The Most Important Scarce Resource is Legitimacy.txt` |
| 2021-08 | 确定事实 | Moving beyond coin voting governance | 明确反对把治理压缩成 coin voting，转向更复杂的反捕获治理。 | https://vitalikblog.w3eth.io/；`020_Moving beyond coin voting governance.txt` |
| 2021-12 | 确定事实 | Endgame | rollup、区块生产集中化风险、验证与抗审查的长期终局想象。 | https://vitalikblog.w3eth.io/；`016_Endgame.txt` |
| 2022-07 | 确定事实 | What do I think about network states? | 关注点从协议扩展到网络国家、社区自治与政治叙事。 | https://vitalikblog.w3eth.io/；`007_What do I think about network states.txt` |
| 2022-09-15 | 确定事实 | The Merge / Paris | Ethereum.org 记载 Paris 升级在 2022-09-15 触发，关闭 PoW 挖矿逻辑并切换到 PoS；该页称其是 Homestead 以来最重要升级之一。 | https://ethereum.org/ethereum-forks/ |
| 2023-06 | 确定事实 | The Three Transitions | 将 L2 scaling、wallet security、privacy 作为 Ethereum 面向主流采用的三大转型。 | https://vitalikblog.w3eth.io/general/2023/06/09/three_transitions.html |
| 2023-11 | 确定事实 | My techno-optimism | d/acc 之前的系统性纲领，把技术进步、AI 风险、开放与防御能力放在同一图景中。 | https://vitalikblog.w3eth.io/general/2023/11/27/techno_optimism.html；`003_My techno-optimism.txt` |
| 2024-03 | 确定事实 | Dencun / blobs | Ethereum.org 记载 Dencun 引入 EIP-4844 / blobs，显著降低 L2 rollup 数据发布成本。 | https://ethereum.org/ethereum-forks/ |
| 2024-05 | 确定事实 | Permissionlessness、L2 文化、multidimensional gas | 2024 年中，他把 L2 不只看成技术层级，也看成文化扩展和权力结构问题。 | https://vitalikblog.w3eth.io/；`001_...permissionlessness and decentralization.txt`、`005_...execution sharding.txt` |
| 2024-09 至 2024-10 | 确定事实 | Ethereum alignment 与未来路线图六部曲 | 进入“让 alignment 可读、可衡量”的阶段，并按 Merge/Surge/Scourge/Verge/Purge/Splurge 系统整理路线图。 | https://vitalikblog.w3eth.io/ |
| 2025-01-05 | 确定事实 | d/acc: one year later | d/acc 框架更明确，把 AI、开放科学、信息防御、身份和安全放入同一个防御性加速框架。 | https://vitalikblog.w3eth.io/general/2025/01/05/dacc2.html；`003_My techno-optimism.txt` |
| 2025-01-18 | 二手报道 / X 转述 | Ethereum Foundation 领导结构变动 | 多家媒体转述 Vitalik 在 X 上表示 EF 正进行领导结构变化，目标包括提高技术能力、改善沟通、支持 dapp 开发者、坚持去中心化/抗审查/隐私，同时不把 EF 变成政治游说组织。 | https://cointelegraph.com/news/buterin-announces-leadership-changes-ethereum-foundation |
| 2025-01-23 | 确定事实 | Scaling Ethereum L1 and L2s in 2025 and beyond | 2025 版路线：L2 继续主导，但 L1 仍需扩容、改善互操作、强化 ETH 经济与基础安全。 | https://vitalikblog.w3eth.io/general/2025/01/23/l1l2future.html；`004_Scaling Ethereum L1 and L2s in 2025 and beyond.txt` |
| 2025-02-14 | 确定事实 | Higher L1 gas limits in an L2-heavy Ethereum | 即使 L2-heavy，L1 仍作为基础安全、简单开发模式和资产发行底座。 | https://vitalikblog.w3eth.io/general/2025/02/14/l1scaling.html |
| 2025-02-28 | 确定事实 | AI as the engine, humans as the steering wheel | AI 被纳入治理和大规模判断，但人类应保留方向盘。 | https://vitalikblog.w3eth.io/general/2025/02/28/aihumans.html；`053_AI, humans and the edges of agency.txt` |
| 2025-03-29 | 确定事实 | Tree ring model / open source funding | 叙事从泛化 public goods funding 更收束到 open source funding，强调可执行与可审计。 | https://vitalikblog.w3eth.io/general/2025/03/29/treering.html；https://vitalikblog.w3eth.io/general/2025/03/29/pubos.html |
| 2025-04-14 | 确定事实 | Why I support privacy | 隐私被更明确描述为去中心化、自主性与抗胁迫的基础条件。 | https://vitalikblog.w3eth.io/general/2025/04/14/privacy.html；`022_Why I support privacy.txt` |
| 2025-05-03 | 确定事实 | Simplifying the L1 | 协议简洁性被提升为安全、可参与研究、长期抗捕获和可维护性的核心目标。 | https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html |
| 2025-05-06 | 确定事实 | Stage 1 / Stage 2 数学化 | Rollup 安全分级进一步工程化和量化。 | https://vitalikblog.w3eth.io/general/2025/05/06/stages.html |
| 2025-06-28 | 确定事实 | ZK-wrapped digital ID risks | 单一 one-person-one-ID 即使用 ZK 包裹，仍可能伤害伪匿名、抗胁迫与容错；更偏向 pluralistic identity。 | https://vitalikblog.w3eth.io/general/2025/06/28/zkid.html；`054_Against biometric identity maximalism.txt` |
| 2025-07-07 | 确定事实 | Favor copyleft | 从早期偏好 permissive license 转向更支持 copyleft，体现对开放性激励和权力集中风险的再评估。 | https://vitalikblog.w3eth.io/general/2025/07/07/copyleft.html；`023_Why I support open source and copyleft.txt` |
| 2025-07-10 | 确定事实 | My response to AI 2027 | 反对只用进攻方超能力叙事建模 AI 风险，强调生物防御、网络安全、信息防御、硬件验证等防御技术也会进步。 | https://vitalikblog.w3eth.io/general/2025/07/10/2027.html |
| 2025-08-12 | 确定事实 | “I support it only if it's open source” | 将开源从开发者偏好提升为高风险技术基础设施的默认判断标准。 | https://vitalikblog.w3eth.io/general/2025/08/12/onlyopensource.html |
| 2025-08-12 | 确定事实 | On idea-driven ideas | 关注 idea-driven 的制度与产品创新，补充其“技术 + 机制 + 文化”混合视角。 | https://vitalikblog.w3eth.io/general/2025/08/12/idea_driven.html |
| 2025-09-21 | 确定事实 | Low-risk DeFi | 低风险 DeFi 被重新评价为 Ethereum 可能的正和收入 / 使用支柱，前提是它与 Ethereum 的文化目标一致。 | https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html |
| 2025-09-24 | 确定事实 | Full-stack openness and verifiability | 开放和可验证性被扩展到软件、硬件、生物技术、AI 和未来脑机接口；核心判断是“互联网已经成为现实生活”。 | https://vitalikblog.w3eth.io/general/2025/09/24/openness_and_verifiability.html |
| 2025-10-05 | 确定事实 | Memory access is O(N^[1/3]) | 持续通过数学 / 计算直觉文章解释底层技术思维。 | https://vitalikblog.w3eth.io/general/2025/10/05/memory.html |
| 2025-10-19 | 确定事实 | A GKR Tutorial | 继续以教程形式降低证明系统理解门槛。 | https://vitalikblog.w3eth.io/general/2025/10/19/gkr.html |
| 2025-11-07 | 确定事实 | Galaxy brain resistance | 延续对“过度复杂 / 过拟合路线图叙事”的警惕。 | https://vitalikblog.w3eth.io/general/2025/11/07/galaxy.html |
| 2025-11-25 | 确定事实 | Plinko PIR tutorial | 继续推进隐私 / PIR 等可验证隐私技术的教育化表达。 | https://vitalikblog.w3eth.io/general/2025/11/25/plinko.html |
| 2025-12-17 | 确定事实 | Let a thousand societies bloom | 将 pluralism 和社会实验进一步扩展到“多种社会形态并行试错”的尺度。 | https://vitalikblog.w3eth.io/general/2025/12/17/thousand.html |
| 2025-12-30 | 确定事实 | Balance of power | 将 Big Government、Big Business、Big Mob 都视为需要制衡的力量；把去中心化提升为文明层面的权力平衡问题。 | https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html |
| 2026-01 | 二手报道 / X 转述 | EF “mild austerity” 与个人资源重定向 | 媒体转述 Vitalik 称 Ethereum Foundation 进入 5 年 mild austerity，并有个人 ETH 资源转向长期技术/生态项目。需以 X 原文或一手链接进一步复核。 | https://www.thecoinrepublic.com/2026/01/30/ethereum-foundation-is-entering-a-period-of-mild-austerity-vitalik-buterin/；https://defi-planet.com/2026/01/vitalik-buterin-commits-16384-eth-to-long-term-ethereum-foundation-projects/ |
| 2026-02-05 | 二手报道 | The Guardian 关于 EF 领导争议 | Guardian 报道 Danny Ryan 领导提案和 Ethereum Foundation 争议，强调 Ethereum 在牛市中错失部分叙事机会，也暴露出政治、权力和价格叙事的内部裂缝。 | https://www.theguardian.com/technology/2026/feb/05/cryptocurrency-ethereum-bitcoin-industry |
| 2026-02 | 二手报道 / X 转述 | 对 prediction markets “corposlop” 的担忧 | Business Insider 等报道 Vitalik 对预测市场过度走向体育/短期 crypto 下注、低社会信息价值产品表示担忧；这延续其“机制要服务公共信息价值，而非上瘾性收入”的判断。 | https://www.businessinsider.com/ethereum-creator-polymarket-backer-raises-concern-about-prediction-markets-future-2026-2；https://tribuna.com/amp/en/casino/news/2026-02-16-vitalik-buterin-warns-prediction-markets-are-drifting-toward-corposlop/ |
| 2026-04-02 | 确定事实 | My self-sovereign / local / private / secure LLM setup | 最新可验证公开博客：将 d/acc、隐私、开源、可验证性落到个人 AI 工作流；强调 local-first、sandbox、人类 + LLM 2-of-2 确认、ZK API、mixnet、TEE、FHE 等多层防御。 | https://vitalikblog.w3eth.io/general/2026/04/02/secure_llms.html |

## 2. 最近 12 个月动态窗口：2025-04-07 至 2026-04-07

### 已确认的一手博客序列

`vitalik.eth.limo` 在部分检索中可能滞后；本次以 `vitalikblog.w3eth.io` 镜像作补充核对。该索引明确列出 2025-04-14 至 2026-04-02 的文章序列：

- 2025-04-14：`Why I support privacy`
- 2025-05-03：`Simplifying the L1`
- 2025-05-06：`The math of when stage 1 and stage 2 make sense`
- 2025-05-11：数学解释文章
- 2025-06-28：`Does digital ID have risks even if it's ZK-wrapped?`
- 2025-07-07：`Why I used to prefer permissive licenses and now favor copyleft`
- 2025-07-10：`My response to AI 2027`
- 2025-08-12：`"I support it only if it's open source" should be a more common viewpoint`
- 2025-08-12：`On idea-driven ideas`
- 2025-09-21：`Low-risk defi can be for Ethereum what search was for Google`
- 2025-09-24：`The importance of full-stack openness and verifiability`
- 2025-10-05：`Memory access is O(N^[1/3])`
- 2025-10-19：`A GKR Tutorial`
- 2025-11-07：`Galaxy brain resistance`
- 2025-11-25：`Plinko PIR tutorial`
- 2025-12-17：`Let a thousand societies bloom`
- 2025-12-30：`Balance of power`
- 2026-04-02：`My self-sovereign / local / private / secure LLM setup, April 2026`

来源：https://vitalikblog.w3eth.io/

### 这一窗口的主轴变化

- **隐私从“权利/功能”升级成“AI 时代的默认安全边界”**：2025-04 隐私、2025-09 全栈可验证、2026-04 本地 LLM 是一条连续线。
- **L1 简化与 L2 路线并行**：2025-01 的 L1/L2 扩容路线在 2025-05 `Simplifying the L1` 中变得更明确：长期安全需要让协议更简单。
- **开源从“价值观”变成“防御性基础设施”**：2025-07 copyleft、2025-08 open-source-only、2025-09 full-stack openness 把开源与权力分散、审计和技术主权绑定。
- **低风险 DeFi 是一次语义修正**：从对投机 DeFi 的谨慎，转向把支付、储蓄、合成资产、充分抵押借贷等低风险 DeFi 看成可与 Ethereum 文化目标一致的经济支柱。
- **d/acc 进入个人工作流**：2026-04 本地 LLM 文章不再只是理念，而是具体到硬件、NixOS、sandbox、human+LLM confirmation、ZK API / mixnet / TEE / FHE。
- **权力平衡成为更大框架**：2025-12 `Balance of power` 将去中心化从 crypto 内部原则扩展为政府、公司、群体三角之间的文明级制衡问题。

## 3. 思想转折点

### 转折 1：从 Bitcoin 作者 / 观察者到 Ethereum 协议架构师

- **时间**：2011-2014
- **证据**：Ethereum.org 记载他 2011 年发现 Bitcoin、2012 年共同创办 Bitcoin Magazine、2013 年构思 Ethereum、2014 年发布白皮书。
- **推断**：他最早的转折不是“从金融到技术”，而是从“解释现有协议”转为“设计更通用的协议”。这奠定了他后来总是把应用、规则、经济和社会层一起看的习惯。

### 转折 2：DAO hard fork 让社会层不可回避

- **时间**：2016
- **证据**：`Onward from the Hard Fork` 与本地 `091_Onward from the Hard Fork.txt`。
- **推断**：DAO 事件之后，合法性、社区共识、fork、软权力和“谁能决定”成为他的长期议题。这不是从技术撤退，而是承认协议是社会技术系统。

### 转折 3：从 sharding 想象到 rollup-centric 和模块化扩容

- **时间**：2020-2025
- **证据**：`An Incomplete Guide to Rollups`、`Endgame`、2024 Dencun blobs、2025 `Scaling Ethereum L1 and L2s in 2025 and beyond`。
- **推断**：扩容不再是单纯“L1 吞吐量”，而是把执行、数据可用性、证明、互操作和退出权重新分配。

### 转折 4：从 cypherpunk 口号到 pluralistic / defensive design

- **时间**：2023-2026
- **证据**：`Make Ethereum Cypherpunk Again`、`Why I support privacy`、`Does digital ID have risks even if it's ZK-wrapped?`、`Balance of power`、本地 `024_Why I’m not a cypherpunk.txt`。
- **推断**：他并非抛弃 cypherpunk，而是把它从个人防御升级为多中心、可验证、可退出、抗胁迫的社会基础设施。

### 转折 5：从公共品 funding 到 open source funding / full-stack verifiability

- **时间**：2025
- **证据**：2025-03 `We should talk less about public goods funding and more about open source funding`、2025-07 copyleft、2025-09 full-stack openness。
- **推断**：这是语义收束：从“公共品”这种容易泛化的词，转向更清晰可审计的开源与可验证技术标准。

### 转折 6：从 AI 风险讨论到本地可控 AI 工作流

- **时间**：2023-2026
- **证据**：`My techno-optimism`、`AI as the engine, humans as the steering wheel`、`My response to AI 2027`、2026-04 `secure LLM setup`。
- **推断**：AI 不再只是外部宏观风险，而是正在进入他的个人安全实践：本地推理、沙箱、人类确认、防提示注入、隐私-preserving remote calls。

## 4. 与本地 100 txt 的交叉验证

### 本地包对时间线的稳定信号

- **早期协议工程**：`088`、`094`、`095`、`100` 支持 2014-2017 的 PoS / scaling / sharding 主轴。
- **DAO 与安全**：`091`、`092`、`093` 支持 2016 后“社会层 + 安全工程”主轴。
- **rollup 与 L2**：`012`、`016`、`035`、`036`、`037` 支持 2020-2025 扩容作为职责重构。
- **治理与合法性**：`010`、`020`、`027`、`030`、`031`、`050` 支持 2021 后 social layer / legitimacy 主轴。
- **AI、隐私、身份、开源**：`022`、`023`、`025`、`053`、`054` 支持 2023-2026 的 d/acc / open-source / privacy 方向。

### 本地包的限制

- 它不是逐字稿，不能用来生成精确引用。
- 它在最近 12 个月上不如 `vitalikblog.w3eth.io` 新；2025-07 到 2026-04 的最新博客必须以在线索引与原文为准。
- 它仍然很适合做“主题延续性”验证：新材料不是突然转向，而是强化了可验证性、开放性、权力平衡、防御性能力扩散这些长期主轴。

## 5. 最新动态的诚实边界

- 本次已经核对 `vitalikblog.w3eth.io` 到 2026-04-02，最新可验证本人博客是 `My self-sovereign / local / private / secure LLM setup, April 2026`。
- `vitalik.eth.limo` 可能在索引或检索层面滞后；不能仅凭该域名检索结果说 2025-06 后没有新文章。
- 2026-01 到 2026-02 的 EF mild austerity、个人 ETH 资源投入、prediction markets “corposlop” 等主要来自二手媒体与 X 转述；最终 Skill 中应标注为二手报道，除非后续拿到可验证 X 原文或本人博客。
- 2026-04-02 后到当前日期 2026-04-07，未检索到比 secure LLM setup 更新的 Vitalik 本人博客。
- 会议、播客和 X 的全量检索可能仍有遗漏；这类遗漏应在最终 Skill 的诚实边界中保留。

## 6. 可转入最终 Skill 的时间线摘要

- **1994-2014**：Bitcoin → Bitcoin Magazine → Ethereum 白皮书，核心转折是从解释协议到设计通用可编程协议。
- **2015-2016**：主网上线、Homestead、DAO hard fork，核心转折是社会层与安全不再可分。
- **2017-2021**：PoS、sharding、rollups、legitimacy、coin voting 批判逐步成型。
- **2022**：The Merge 完成，PoS 从长期路线变成现实。
- **2023-2024**：三大转型、d/acc、Dencun blobs、L2 文化、Ethereum alignment 与路线图六部曲。
- **2025**：L1/L2 2025 路线、L1 简化、privacy、ZK identity 风险、copyleft、open-source-only、full-stack openness、low-risk DeFi、balance of power。
- **2026-04**：本地 / 私有 / 安全 LLM 设置，把 d/acc 落到个人 AI 工作流。

## 7. 主要来源

### 一手 / 官方

- Vitalik blog index: https://vitalikblog.w3eth.io/
- Secure LLM setup: https://vitalikblog.w3eth.io/general/2026/04/02/secure_llms.html
- Balance of power: https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html
- Full-stack openness and verifiability: https://vitalikblog.w3eth.io/general/2025/09/24/openness_and_verifiability.html
- Low-risk DeFi: https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html
- Ethereum history / founder: https://ethereum.org/zh/ethereum-history-founder-and-ownership/
- Ethereum forks timeline: https://ethereum.org/ethereum-forks/
- Ethereum whitepaper: https://ethereum.org/whitepaper/
- Ethereum Foundation blog: https://blog.ethereum.org/
- Ethereum Research: https://ethresear.ch/

### 二手 / 外部动态

- Guardian, Ethereum Foundation leadership controversy, 2026: https://www.theguardian.com/technology/2026/feb/05/cryptocurrency-ethereum-bitcoin-industry
- Cointelegraph, EF leadership changes, 2025: https://cointelegraph.com/news/buterin-announces-leadership-changes-ethereum-foundation
- Business Insider, prediction markets concern, 2026: https://www.businessinsider.com/ethereum-creator-polymarket-backer-raises-concern-about-prediction-markets-future-2026-2
- The Coin Republic, EF mild austerity report, 2026: https://www.thecoinrepublic.com/2026/01/30/ethereum-foundation-is-entering-a-period-of-mild-austerity-vitalik-buterin/
- Defi Planet, 16,384 ETH report, 2026: https://defi-planet.com/2026/01/vitalik-buterin-commits-16384-eth-to-long-term-ethereum-foundation-projects/

### 本地语料

- `local-vitalik_100_txt/README.txt`
- `local-vitalik_100_txt/001_...txt` 到 `local-vitalik_100_txt/100_...txt`
