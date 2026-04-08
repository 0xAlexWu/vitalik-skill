# Vitalik Buterin v2 决策研究

> 维度 5：重大决策、转折点、争议行为与可转化为启发式的行动逻辑。
>
> 写作说明：本文件用于后续生成 `vitalik-buterin-perspective/SKILL.md`，不是最终 Skill。所有结论尽量区分「Vitalik 公开说过 / 写过的」「外部观察」「我基于多源材料的推断」。

## 0. 研究范围与证据分级

### 纳入材料

- 一手 / 近一手：Vitalik 个人博客与镜像、Ethereum Foundation Blog、Ethereum Research、ethereum.org 路线图与公开访谈。
- 本地语料：`local-vitalik_100_txt` 下 100 个编号 txt。该目录是摘要学习包，不是逐字原文；它适合作为主题地图、证据索引和交叉对照，不适合作为精确引文来源。
- 外部视角：主流媒体、学术研究与社区报道，仅用于识别争议、盲点和事实软权力，不替代 Vitalik 本人材料。

### 证据分级

- `[一手]` Vitalik 本人文章、Ethereum Foundation 署名文章、Ethereum Research 帖、官方路线图。
- `[近一手]` 长访谈、播客、会议对话、公开 X 发言的可信转述。
- `[二手]` 媒体、学术论文、社区摘要、本地 `vitalik_100_txt` 摘要包。
- `[推断]` 我从多篇材料重复模式中归纳出的决策规则。

## 1. 总判断

Vitalik 的重大决策逻辑不是「最大化单一目标」，而是把每个选择放到四个长期约束里：

1. **验证**：用户和第三方能否独立检查系统？
2. **退出**：如果中心变坏，用户能否离开、分叉、替代？
3. **复杂性边界**：复杂度是否进入 consensus-critical 绿色区？
4. **合法性 / 权力平衡**：这个选择会让谁更有权力？是否会削弱生态长期正当性？

这使他的决策常常看起来慢、绕、过度谨慎，但稳定地服务于一个目标：让开放系统在规模化以后仍然不变成单点控制机器。

## 2. 决策主线 A：Ethereum 从一开始就不是「只做币」

### 他说过 / 写过的

- [一手] `The Evolution of Ethereum` 说 Ethereum 来自一个判断：blockchains can go far beyond currency，核心想法是带内置图灵完备语言的区块链，让用户在其上构建各种应用。来源：https://blog.ethereum.org/2015/09/28/the-evolution-of-ethereum
- [一手] 同文把 Ethereum 扩展为更大的 web3 视野：更安全、可信、全球可访问的互联网，用于 agreements、finance、auditing、tracking 等。来源：https://blog.ethereum.org/2015/09/28/the-evolution-of-ethereum
- [二手] 本地摘要 `086_On Public and Private Blockchains.txt`、`087_On Bitcoin Maximalism, and Currency and Platform Network Effects.txt`、`090_The Evolution of Ethereum.txt` 共同支持：早期 Vitalik 不接受 Bitcoin maximalism 的单一货币叙事，而是把区块链看作更通用的协议平台。

### 决策含义

- [推断] 他选择 Ethereum，不是为了做「更快的 Bitcoin」，而是做一套可编程的协调基础设施。
- [推断] 这解释了他后来为何长期愿意承受更高协议复杂度：因为目标不是最小货币协议，而是世界计算 / 世界账本 / 可验证应用平台。

### 可转化启发式

- 如果一个设计只优化资产价格或交易速度，却不能拓展可验证应用与协调能力，它不是 Vitalik 式主线。
- 评估新协议时，不只问「它是不是钱」，还要问「它能否让更多可信协调变成无需许可的基础设施」。

## 3. 决策主线 B：Ethereum Foundation 逐步去中心化，但软权力没有消失

### 他说过 / 写过的

- [一手] 2015 年 `The Evolution of Ethereum` 明确写到，Ethereum 的未来不能只靠 Foundation 和子公司；社区驱动是必要的，因为项目已超出 Foundation 人力和资金能独自完成的范围。来源：https://blog.ethereum.org/2015/09/28/the-evolution-of-ethereum
- [一手] 同文列出 Foundation 应更聚焦：教育、会议、合规、核心开发、研究、规范；更高层开发将更多由 for-profit entities、volunteers 和社区完成。来源：https://blog.ethereum.org/2015/09/28/the-evolution-of-ethereum

### 外部观察

- [二手] 外部研究和媒体常指出 Ethereum 治理透明但并不平坦，Vitalik 与 EF 仍有事实软权力。v2 外部视角维度已收录 TIME、WIRED、VICE、Guardian、Business Insider、SSRN 与 De Filippi 等材料，本决策维度将其保留为重要张力。

### 决策含义

- [推断] Vitalik 早就知道「中心必须退后」，但退后不是消失，而是从直接控制变成路线图、写作、研究资助和社会层影响。
- [推断] 他的很多文章是在做软治理：不用命令，而是把生态的默认问题框架改掉。

### 可转化启发式

- 去中心化不是宣布无领导，而是把中心的职责缩到必要范围，并让替代路径真实存在。
- 当你说「社区驱动」时，必须问：核心规范、资金、路线图、客户端、研究议程是否仍被少数人事实上控制？

## 4. 决策主线 C：DAO hard fork 让合法性成为硬约束

### 他说过 / 写过的

- [一手] `Onward from the Hard Fork` 是 DAO 分叉后的官方沟通节点，标志着 Ethereum 不得不把协议执行与社会共识放到同一层处理。来源：https://blog.ethereum.org/2016/07/26/onward-from-the-hard-fork
- [一手] 2021 年 `The Most Important Scarce Resource is Legitimacy` 将 legitimacy 明确建模为稀缺资源，而不是宣传词。来源：https://vitalik.eth.limo/general/2021/03/23/legitimacy.html
- [二手] 本地摘要 `010_The Most Important Scarce Resource is Legitimacy.txt`、`030_Control as a liability.txt`、`077_Endnotes on Ethereum roadmaps and social process.txt` 支持：他把 fork / upgrade / governance 看成合法性管理，而不是纯技术执行。

### 决策含义

- [推断] DAO hard fork 之后，他不再可能把协议治理描述成「代码就是法律」的简单故事。
- [推断] 他后续重视退出权、分叉、社会层、公共讨论和路线图合法性，是从这次事件强化出来的。

### 张力

- [推断] DAO hard fork 是「保护用户」与「不可篡改」之间的冲突。Vitalik 视角不会把它简单洗成胜利，也不会简单判成背叛；它是合法性与可执行规则之间的永久案例。

### 可转化启发式

- 重大协议决策不能只问「技术上能不能」，还要问「社区会不会把它视为正当」。
- 如果一次干预需要社会层授权，必须诚实承认这是社会层决策，而不是伪装成纯代码逻辑。

## 5. 决策主线 D：PoS / The Merge 是硬件门槛、长期安全与可持续性的路线选择

### 他说过 / 写过的

- [一手] 2014 年 `Slasher` 已经显示 Vitalik 很早就把 PoS 与惩罚机制当成核心研究方向。来源：https://blog.ethereum.org/2014/01/15/slasher-a-punitive-proof-of-stake-algorithm
- [一手] ethereum.org 的 Merge 路线图记录 Ethereum 从 PoW 转向 PoS 的完成节点，并将其放在长期升级路线中。来源：https://ethereum.org/roadmap/merge/
- [二手] 本地摘要 `088_Slasher A Punitive Proof-of-Stake Algorithm.txt`、`073_CBC Casper and consensus intuition.txt`、`075_Epochs, slots and consensus ergonomics.txt` 支持：PoS 不是 2022 临时决定，而是从早期就持续推进的长期路线。

### 决策含义

- [推断] PoS 的核心不是「环保」单点叙事，而是降低系统运行成本、降低硬件与能源门槛、把安全预算转化为可治理的机制设计问题。
- [推断] The Merge 的决策风格是：愿意多年承受路线复杂度，换取长期更低系统性成本。

### 张力

- [推断] PoS 也带来财富集中、staking pool 集中、治理感知中心化等新风险。Vitalik 后续对 Lido、dual governance、validator democratization、3-slot finality 的关注，是在继续修补这条路线的副作用。

### 可转化启发式

- 如果一次迁移能显著降低长期系统性成本，即使短期很难，也值得坚持。
- 但任何「降低资源门槛」的机制，都要同步检查是否引入新的权力集中形式。

## 6. 决策主线 E：扩容路线从 sharding 转为 rollup-centric，再转向 L1 + L2 双强化

### 他说过 / 写过的

- [一手] `The Limits to Blockchain Scalability` 将扩容放在普通节点可验证能力的边界内讨论。来源：https://vitalik.eth.limo/general/2021/05/23/scaling.html
- [一手] `Why sharding is great` 解释分片的技术属性与去中心化目标。来源：https://vitalik.eth.limo/general/2021/04/07/sharding.html
- [一手] 2025 年 `Scaling Ethereum L1 and L2s in 2025 and beyond` 显示新阶段：L2 继续主导，但 L1 也需要提高容量、互操作性与安全底座。来源：https://vitalikblog.w3eth.io/general/2025/01/23/l1l2future.html
- [二手] 本地摘要 `004_Scaling Ethereum L1 and L2s in 2025 and beyond.txt`、`005_How do layer 2s really differ from execution sharding.txt`、`012_An Incomplete Guide to Rollups.txt`、`035_A short guide to blobs and proto-danksharding.txt`、`036_Multidimensional gas pricing in Ethereum.txt`、`037_Why sharding is great demystifying the technical properties.txt`、`040_Plasma versus sharding.txt` 支持这条演化。

### 决策含义

- [推断] Vitalik 的扩容决策不是「吞吐最大化」，而是把执行、数据可用性、验证、桥风险和社会协调重新分配到不同层。
- [推断] rollup-centric 路线允许生态实验和文化多样性，但必须用互操作、退出机制和 L1 安全底座防止碎片化变成事实中心化。

### 张力

- L2 多样性 vs 用户体验统一。
- L1 安全 / 简洁 vs L1 容量增长。
- 异构执行环境 vs 共享安全与可组合性。

### 可转化启发式

- 扩容时不要先问 TPS；先问「谁验证、谁保存数据、谁承担桥风险、用户如何退出」。
- 如果 L2 变得太像封闭平台，rollup-centric 的去中心化收益会被吃掉。

## 7. 决策主线 F：2025 L1 简化，把协议简洁性提升为治理与韧性目标

### 他说过 / 写过的

- [一手] `Simplifying the L1` 说 Ethereum 要成为 world ledger，需要 scalability 和 resilience，而协议 simplicity 是同样重要、容易被低估的韧性来源。来源：https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html
- [一手] 同文列出简洁性的收益：更多人能参与研究 / 治理，降低新基础设施成本，降低长期维护成本，减少灾难性 bug，减少社会攻击面。来源：https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html
- [一手] 同文承认 Ethereum 历史上常没做到这一点，并说这部分有时来自他自己的决定。来源：https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html
- [一手] 同文提出可能用 RISC-V 或更简单 VM 替代 EVM，以少数更有意义的破坏性变更换取 100x 级别简化。来源：https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html

### 决策含义

- [推断] 这是一个重要转折：Vitalik 不再只把复杂性看作「功能代价」，而是把它看作治理参与门槛、安全风险和被技术官僚捕获的路径。
- [推断] 他愿意为大幅简化接受少数重大迁移，这与他对 Merge 的长期主义风格一致。

### 张力

- 简化 vs 向后兼容。
- 绿色区 consensus-critical 复杂度 vs 黄色/橙色区封装复杂度。
- 立刻可用的小改进 vs 多年后实现的 100x 简化。

### 可转化启发式

- 如果一个设计降低绿色区复杂度，它的价值不能只用短期性能衡量。
- 能把复杂度从 systemic 变成 encapsulated，就已经是重大治理改进。

## 8. 决策主线 G：治理不是 coin voting，而是 pluralism、veto、合法性与反串谋

### 他说过 / 写过的

- [一手] `Moving beyond coin voting governance` 反对把治理简化为币权投票。来源：https://vitalik.eth.limo/general/2021/08/16/voting3.html
- [二手] 本地摘要 `020_Moving beyond coin voting governance.txt`、`046_On collusion.txt`、`048_On pluralism and veto systems.txt`、`050_DAOs, governance, and institutional design.txt`、`080_Gini, inequality and crypto governance.txt` 支持：他长期关注鲸鱼、串谋、懒惰投票、利益冲突和治理权力范围。

### 决策含义

- [推断] 他不是反治理，而是反「把所有治理压到一个可买卖的投票变量」。
- [推断] 他偏好约束治理作用域、引入延迟、多元参与、否决权和退出机制。

### 可转化启发式

- 当一个 DAO 说自己民主，先看它是否只是 coin voting。
- 好治理通常不是投票更频繁，而是让少数关键问题有足够合法性、退出权和反串谋设计。

## 9. 决策主线 H：隐私与身份，从 cypherpunk 口号走向 pluralistic defensive infrastructure

### 他说过 / 写过的

- [一手] 2025 年 `Why I support privacy` 把隐私作为去中心化和抗胁迫的重要条件。来源：https://vitalik.eth.limo/general/2025/04/14/privacy.html
- [二手] 本地摘要 `022_Why I support privacy.txt`、`024_Why I’m not a cypherpunk.txt`、`049_My journey from defense to decentralization.txt`、`054_Against biometric identity maximalism.txt`、`056_The backpack problem of digital identity.txt` 支持：他不是标准 cypherpunk 纯主义，而是把隐私、可验证、身份、社会协调一起设计。

### 决策含义

- [推断] Vitalik 对身份的决策原则不是「去中心化身份一定好」，而是避免单一身份根、单一生物识别根、单一 one-person-one-ID 根变成胁迫和去匿名化工具。
- [推断] ZK 是缓解工具，但不是魔法。即使 ZK-wrapped digital ID 仍要看伪匿名、胁迫、错误恢复和可替代性。

### 可转化启发式

- 身份系统要默认 pluralistic，不要让一个证明根绑定全部社会身份。
- 如果一个隐私方案要求用户相信中心不会滥用，它还不够 Vitalik 式。

## 10. 决策主线 I：AI / open source / d/acc 从理念转向实际安全工作流

### 他说过 / 写过的

- [一手] `My response to AI 2027` 反对只假设进攻方获得 AI 超能力，而防御方能力停留原地；他主张把 AI 能力同时带来的生物防御、网络安全、信息防御等反制能力纳入模型。来源：https://vitalikblog.w3eth.io/general/2025/07/10/2027.html
- [一手] `I support it only if it's open source` 把 open source 描述为第三条路：既不是停下技术，也不是接受专有平台；开源改善平等访问、生产者访问、可验证性，并减少 vendor lock-in。来源：https://vitalikblog.w3eth.io/general/2025/08/12/onlyopensource.html
- [一手] `The importance of full-stack openness and verifiability` 将开放与可验证性扩展到软件、硬件、生物技术、政府流程、环境监测、未来 BCI 等全栈技术。来源：https://vitalikblog.w3eth.io/general/2025/09/24/openness_and_verifiability.html
- [一手] 2026-04-02 `My self-sovereign / local / private / secure LLM setup` 将隐私、安全和 self-sovereignty 当作非协商目标：local inference、local files、sandbox everything、对外部互联网威胁保持偏执。来源：https://vitalikblog.w3eth.io/general/2026/04/02/secure_llms.html
- [一手] 同文提出 Signal/email daemon 的严格 firewall：自主只能读消息和发给自己；发给他人必须人工确认；连接 Ethereum 钱包也应采用同类 human + LLM 2-of-2 confirmation。来源：https://vitalikblog.w3eth.io/general/2026/04/02/secure_llms.html

### 决策含义

- [推断] d/acc 不只是宏观政治姿态，它已经进入工具链：本地模型、沙箱、人工确认、防提示注入、ZK API、mixnet、TEE、未来 FHE。
- [推断] 他对 AI 的核心决策不是「AI 要不要发展」，而是「谁拥有运行环境、数据、审计能力和防御能力」。

### 张力

- 开源 AI vs 滥用扩散。
- 本地模型隐私 vs 远程模型能力。
- TEE 等硬件信任 vs 纯密码学安全。
- human confirmation 的安全收益 vs UX 摩擦。

### 可转化启发式

- AI agent 要处理钱、消息或身份时，不要默认全自动；高风险动作至少需要 human + LLM 2-of-2。
- 能本地优先就本地优先；必须远程时，尽量用 ZK API、mixnet、TEE、输入清洗、最小化泄露等多层防御。
- Open weights 不等于 open source；评估 AI 开放性时要问训练过程、数据、工具链、可验证性是否也开放。

## 11. 决策主线 J：公共品、开源资金与低风险 DeFi的语义收束

### 他说过 / 写过的

- [二手] 本地摘要 `067_Quadratic funding, Gitcoin and public goods.txt`、`055_A note on charity.txt` 说明他长期把公共品资金视为 crypto 最有意义的正和应用之一。
- [一手] 2025 年 `Low-risk defi can be for Ethereum what search was for Google` 认为 Ethereum 社区长期有一个张力：经济可持续的应用与符合 Ethereum 初始目标的应用往往脱节；低风险 DeFi 可能同时满足两者。来源：https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html
- [一手] 同文把 low-risk DeFi 定义为 payments、savings、synthetic assets、fully collateralized lending、这些资产之间交换等；其目标是让全球用户 permissionlessly access mainstream assets。来源：https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html
- [一手] 同文批评投机代币、政治 memecoins 等不能作为 Ethereum 改变世界的正当性核心。来源：https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html

### 决策含义

- [推断] Vitalik 在 2025 的重要变化不是放弃公共品，而是把生态可持续性从抽象 public goods 叙事，收束到更可解释、更能产生经济支持、且不违背文化目标的应用类别。
- [推断] low-risk DeFi 是他试图解决「Ethereum 如何同时赚钱和不丢灵魂」的答案之一。

### 张力

- DeFi 贡献费用和 ETH 需求，但过度投机会扭曲文化。
- 非金融应用更接近 Ethereum 理想，但往往难以支撑经济规模。
- 低风险 DeFi 仍有尾部风险、oracle 风险、监管风险和 UX 风险。

### 可转化启发式

- 一个生态的收入来源必须能被社区直视；如果最大应用让你不好意思公开承认，合法性会长期受损。
- 优先支持那些同时有经济可持续性和文化一致性的应用。

## 12. 决策主线 K：Balance of Power 把去中心化上升为文明尺度的权力设计

### 他说过 / 写过的

- [一手] 2025-12-30 `Balance of power` 同时讨论 Big Government、Big Business、Big Mob，认为我们喜欢进步，但害怕历史上最强的进步生成器，因为它们会集中权力。来源：https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html
- [一手] 同文把核心问题定义为：如何在 21 世纪保持繁荣进步，同时避免极端权力集中？他的回答是 mandate more diffusion，包括开源 / copyleft、非竞业限制、adversarial interoperability、Plurality、d/acc 等。来源：https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html
- [一手] 同文将 d/acc 定位为让多极世界更安全的互补策略：开放、可用的防御技术跟上进攻，降低出于安全恐惧而集中权力的需求。来源：https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html

### 决策含义

- [推断] Vitalik 的「去中心化」已经不只是区块链属性，而是权力政治哲学：避免任何政府、公司、群体动员或协议中心成为 hegemonic actor。
- [推断] 这解释了他为何同时支持开源、copyleft、d/acc、adversarial interoperability、plurality 和低风险经济应用：这些都是扩散控制权的不同工具。

### 可转化启发式

- 当一个组织变大，不只看它是否善良，要看它是否会变成无法制衡的环境塑造者。
- 真正值得鼓励的是 `power to`，不是 `power over`：让自己有能力，同时也扩散能力给别人。

## 13. 本地 100 txt 对决策风格的信号

### 技术扩容 / 架构簇

- 本地文件：`001`, `004`, `005`, `006`, `009`, `012`, `032`, `034`, `035`, `036`, `037`, `038`, `039`, `040`, `045`, `057`, `058`, `068`, `069`, `073`, `075`, `077`, `085`, `097`, `099`, `100`
- [推断] 共同信号：扩容是验证、数据可用性、节点负担、互操作、复杂性边界和社会接受度的组合问题，不是 gas / TPS 单变量。

### 治理 / 合法性 / 公共品簇

- 本地文件：`010`, `020`, `027`, `028`, `029`, `030`, `031`, `042`, `046`, `047`, `048`, `050`, `052`, `055`, `067`, `072`, `074`, `080`, `082`
- [推断] 共同信号：他关心谁能退出、谁承担失败成本、哪些机制能抵抗串谋，以及合法性如何从过程和可接受性中产生。

### 隐私 / 身份 / AI / 开放性簇

- 本地文件：`022`, `023`, `024`, `025`, `026`, `053`, `054`, `056`, `059`, `081`, `086`, `092`, `093`, `098`
- [推断] 共同信号：他把开放、隐私、可验证和抗集中化视为同一组约束；AI 和身份只是这组约束进入更高风险领域后的新实例。

## 14. 最值得写入最终 Skill 的决策启发式

1. **先问谁能验证、谁能退出、谁承担失败成本。**
   - 来源：`A Philosophy of Blockchain Validation`、`Legitimacy`、`Control as a liability`、本地 `013/010/030`。

2. **能不进 consensus layer，就不要进 consensus layer。**
   - 来源：`Do not overload the consensus layer`、`Simplifying the L1`、本地 `032/045/077`。

3. **复杂度要从 systemic 变成 encapsulated。**
   - 来源：`Simplifying the L1`、本地 `045_Encapsulated vs systemic complexity in protocol design.txt`。

4. **治理不能只靠 coin voting。**
   - 来源：`Moving beyond coin voting governance`、本地 `020/048/050/080`。

5. **身份系统要 pluralistic，不要单一身份根。**
   - 来源：`Against biometric identity maximalism`、`The backpack problem of digital identity`、本地 `054/056`。

6. **开放与可验证是防御基础设施，不是情怀。**
   - 来源：`I support it only if it's open source`、`Full-stack openness and verifiability`、本地 `023/025/026`。

7. **高风险 AI agent 需要 human + LLM 2-of-2 confirmation。**
   - 来源：`My self-sovereign / local / private / secure LLM setup, April 2026`。

8. **生态收入来源必须和文化目标相容。**
   - 来源：`Low-risk defi can be for Ethereum what search was for Google`。

9. **低风险、正和、可解释的金融应用优于让生态尴尬的投机应用。**
   - 来源：`Low-risk defi...` 与本地 `008/041/060-067`。

10. **权力平衡比单纯反中心化口号更可操作。**
   - 来源：`Balance of power`。

## 15. 关键张力

- 去中心化理想 vs Vitalik / EF 的事实软权力。
- 协议简洁性 vs Ethereum 作为通用平台的复杂需求。
- Rollup 多样性 vs 统一 UX 与安全可理解性。
- 开源 AI / copyleft / mandatory diffusion vs 滥用扩散。
- 本地私有 AI vs 远程大模型能力。
- 公共品叙事 vs 开源资金和低风险 DeFi 的可持续性。
- 低风险 DeFi 的文化一致性 vs DeFi 天生的金融化激励。
- 权力扩散 vs 脆弱世界假说下的安全集中诱惑。

## 16. 诚实边界

- 本文件使用公开资料和本地摘要包，不声称读取 Vitalik 私下动机。
- 本地 100 txt 是摘要学习包，不是逐字原文；精确措辞需回到源链接。
- `vitalik.eth.limo`、`vitalikblog.w3eth.io` 是镜像 / 访问路径，若索引存在差异，最终 Skill 应标注调研时间与镜像边界。
- 2026-04-07 之后的新文章、X 发言、采访和 Ethereum 治理事件未覆盖。
- 对全新问题，只能给出基于上述决策模型的 best guess，不能当作本人确定立场。

## 17. 主要来源

### 一手 / 近一手来源

- Ethereum Foundation Blog: `The Evolution of Ethereum` — https://blog.ethereum.org/2015/09/28/the-evolution-of-ethereum
- Ethereum Foundation Blog: `Onward from the Hard Fork` — https://blog.ethereum.org/2016/07/26/onward-from-the-hard-fork
- Ethereum Foundation Blog: `Slasher: A Punitive Proof-of-Stake Algorithm` — https://blog.ethereum.org/2014/01/15/slasher-a-punitive-proof-of-stake-algorithm
- Ethereum roadmap: `The Merge` — https://ethereum.org/roadmap/merge/
- Vitalik: `The Most Important Scarce Resource is Legitimacy` — https://vitalik.eth.limo/general/2021/03/23/legitimacy.html
- Vitalik: `The Limits to Blockchain Scalability` — https://vitalik.eth.limo/general/2021/05/23/scaling.html
- Vitalik: `Moving beyond coin voting governance` — https://vitalik.eth.limo/general/2021/08/16/voting3.html
- Vitalik: `Why I support privacy` — https://vitalik.eth.limo/general/2025/04/14/privacy.html
- Vitalik: `Scaling Ethereum L1 and L2s in 2025 and beyond` — https://vitalikblog.w3eth.io/general/2025/01/23/l1l2future.html
- Vitalik: `Simplifying the L1` — https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html
- Vitalik: `My response to AI 2027` — https://vitalikblog.w3eth.io/general/2025/07/10/2027.html
- Vitalik: `"I support it only if it's open source" should be a more common viewpoint` — https://vitalikblog.w3eth.io/general/2025/08/12/onlyopensource.html
- Vitalik: `Low-risk defi can be for Ethereum what search was for Google` — https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html
- Vitalik: `The importance of full-stack openness and verifiability` — https://vitalikblog.w3eth.io/general/2025/09/24/openness_and_verifiability.html
- Vitalik: `Balance of power` — https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html
- Vitalik: `My self-sovereign / local / private / secure LLM setup, April 2026` — https://vitalikblog.w3eth.io/general/2026/04/02/secure_llms.html

### 本地语料

- `local-vitalik_100_txt/README.txt`
- `local-vitalik_100_txt/001_...txt` 到 `local-vitalik_100_txt/100_...txt`

### 二手 / 外部材料

- 媒体和社区关于 low-risk DeFi、prediction markets、AI agent security 的报道只用于辅助定位公开事件，不作为核心立场来源。
