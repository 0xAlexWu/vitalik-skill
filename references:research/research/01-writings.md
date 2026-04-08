# Vitalik Buterin v2 写作与系统思考调研

> 维度：01-writings  
> 目标：从 Vitalik 的本人长文、白皮书、Ethereum Foundation 早期文章、Ethereum Research 帖、成书材料与本地 100 篇摘要包中，提炼可用于最终 Skill 的候选心智模型。  
> 调研时间：2026-04-07  
> 黑名单：未使用知乎、微信公众号、百度百科/百度知道。

## 0. 来源分级与方法说明

### 0.1 来源分级

- [一手] Vitalik 本人公开写作：Ethereum whitepaper、Vitalik blog / GitHub-backed blog、Ethereum Foundation blog、Ethereum Research。
- [一手/近一手] `Proof of Stake: The Making of Ethereum and the Philosophy of Blockchains`，由 Vitalik Buterin 著、Nathan Schneider 编辑，Seven Stories Press 2022-09-27 出版；它是本人文章合集，编辑引介不是 Vitalik 原文。
- [二手] 本地 `local-vitalik_100_txt` 摘要包：100 份中文学习笔记，覆盖 85 篇 Vitalik personal blog、10 篇 Ethereum Foundation blog、5 篇 Ethereum Research。它不是逐字稿，适合做主题聚类和来源索引，不适合当精确引文依据。
- [二手] 外部出版/媒体页面用于核对书籍、时间和公开影响，不作为核心思想来源。
- [推断] 本文件中“心智模型”“启发式”“张力”是根据跨文本重复模式归纳，不是 Vitalik 明说的自我定义。

### 0.2 本地 100 txt 语料概况

- `README.txt` 明确说明：每个 txt 包含标题、channel、source、tags、详细中文摘要；优先选择被频繁引用的代表性文章和研究帖。
- Channel 分布：85 篇 Vitalik personal blog、10 篇 Ethereum Foundation blog、5 篇 Ethereum Research。
- Tags 分布：
  - 23 篇：`ethereum, long-term design`
  - 14 篇：`philosophy, technology and society`
  - 14 篇：`governance, social layer`
  - 13 篇：`economics, mechanism design`
  - 10 篇：`scaling, ethereum roadmap`
  - 7 篇：`cryptography, proof systems`
  - 5 篇：`user experience, identity`
- 标题高频词显示他的写作不是“口号驱动”，而是“问题/概念驱动”：`what`、`why`、`governance`、`ethereum`、`layer`、`money`、`proof`、`scalability`、`decentralization`、`consensus`、`AI` 等反复出现。

## 1. 一句话结论

[推断] Vitalik 的系统性写作不是围绕“Ethereum 应该涨/应该赢”展开，而是在长期维护一张协议-社会-制度-技术风险的多层仪表盘。

他反复追问的不是单一指标，而是：

- 谁能验证？
- 谁能退出？
- 复杂性应该放在哪一层？
- 谁被赋权，谁被迫信任？
- 协调和合法性如何产生？
- 开放性、隐私、可验证性和滥用风险如何同时处理？

这套问题从 2013/2014 年 Ethereum 白皮书和 PoS / DAO 早期文章，一直延伸到 2025-2026 年的全栈开放、权力平衡和本地安全 LLM 设置。

## 2. 主要写作谱系

### 2.1 白皮书与平台化起点

**核心样本**

- [一手] Ethereum whitepaper: https://ethereum.org/en/whitepaper/
- [本地摘要/源索引] `090_The Evolution of Ethereum.txt`（摘要指向一手文章，文件本身不是逐字稿）
- [本地摘要/源索引] `086_On Public and Private Blockchains.txt`（摘要指向一手文章，文件本身不是逐字稿）
- [二手/出版核对] Seven Stories Press: `Proof of Stake` book page, https://sevenstories.com/books/4443-proof-of-stake

**观察**

- [一手] Ethereum whitepaper 的基本动作是把 Bitcoin 的“状态转换 + 共识”扩展为可编程平台，而不是只做一种更快的货币。
- [二手] Seven Stories Press 对 `Proof of Stake` 的出版介绍也把他的早期思路定位为“比数字货币更宽的社会、组织和经济想象”，但这属于出版方概括，不能当作 Vitalik 原话。
- [推断] 早期 Vitalik 的独特性在于：他不是只看到“去中心化货币”，而是看到“共享状态机 + 激励 + 脚本能力”可以重新打开制度设计空间。

**可提炼信号**

- 候选模型：区块链是一种可验证协调基础设施，而不只是资产系统。
- 风险：这种宏大平台化叙事容易被后来的金融投机、NFT / memecoin 热潮吞没。

### 2.2 扩容与分层架构线

**核心样本**

- `004_Scaling Ethereum L1 and L2s in 2025 and beyond.txt`
- `005_How do layer 2s really differ from execution sharding.txt`
- `009_The Limits to Blockchain Scalability.txt`
- `012_An Incomplete Guide to Rollups.txt`
- `016_Endgame.txt`
- `032_Do not overload the consensus layer.txt`
- `035_A short guide to blobs and proto-danksharding.txt`
- `036_Multidimensional gas pricing in Ethereum.txt`
- `037_Why sharding is great demystifying the technical properties.txt`
- `038_The meaning of layer 1.txt`
- `039_What kind of layer 3s make sense.txt`
- `045_Encapsulated vs systemic complexity in protocol design.txt`
- `057_Binius and the future of proof systems.txt`
- `058_Circle STARKs and proof engineering.txt`
- `068_GKR proofs and practical scalability.txt`
- `069_Halo proofs and recursive verification.txt`
- `097_On-chain scaling to potentially ~500 txsec through mass tx validation.txt`
- `099_Hyper-scaling state by creating new forms of state.txt`
- `100_A model for stage 4 “tightly coupled” sharding plus full Casper.txt`
- [一手] `The math of when stage 1 and stage 2 make sense`, 2025-05-06, https://vitalikblog.w3eth.io/general/2025/05/06/stages.html
- [一手] `Simplifying the L1`, 2025-05-03, https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html

**观察**

- [一手] 早期 scaling 系列已经把扩容看成验证负担、节点成本、链上/链下结构的组合问题。
- [一手] `Do not overload the consensus layer` 和 `Encapsulated vs systemic complexity` 说明 Vitalik 长期警惕把应用复杂性推进共识层。
- [一手] 2025 年 `Simplifying the L1` 把“协议简洁性”本身提升为安全、参与门槛和抗社会攻击的关键目标。
- [一手] `The math of when stage 1 and stage 2 make sense` 将 rollup 安全阶段形式化，体现他把社会信任和密码学保障转换为分级工程标准的倾向。

**可提炼信号**

- 候选模型：扩容不是 TPS 增长，而是执行、数据可用性、验证、故障恢复和社会信任边界的重新分配。
- 候选模型：复杂性有位置，核心层的复杂性比边缘层复杂性危险得多。
- 决策启发式：能不进 consensus layer，就不要进 consensus layer；除非它是全局一致性必须承载的功能。

### 2.3 治理、合法性与社会层线

**核心样本**

- `010_The Most Important Scarce Resource is Legitimacy.txt`
- `020_Moving beyond coin voting governance.txt`
- `027_The future of institutions.txt`
- `028_Coordination as infrastructure.txt`
- `029_The many kinds of coordination problems.txt`
- `030_Control as a liability.txt`
- `031_Balance of power and the social layer.txt`
- `046_On collusion.txt`
- `047_Notes on cities, governance and digital institutions.txt`
- `048_On pluralism and veto systems.txt`
- `050_DAOs, governance, and institutional design.txt`
- `067_Quadratic funding, Gitcoin and public goods.txt`
- `072_ABC and blockchain governance, revisited.txt`
- `074_Can blockchain improve elections.txt`
- `080_Gini, inequality and crypto governance.txt`
- `082_Concave governance and institutional moderation.txt`
- `091_Onward from the Hard Fork.txt`
- [一手] `Balance of power`, 2025-12-30, https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html

**观察**

- [一手] DAO hard fork 之后，治理不再是抽象兴趣，而变成 Ethereum 必须处理的现实问题。
- [一手] `The Most Important Scarce Resource is Legitimacy` 把合法性当作协调资源，而不是 PR 叙事。
- [一手] `Moving beyond coin voting governance` 和 `Concave governance` 反复警惕单变量投票、鲸鱼治理、串谋和投票权过度金融化。
- [一手] 2025 年 `Balance of power` 将去中心化从 crypto 范畴提升为“大政府、大公司、大群体动员”之间的权力制衡框架。

**可提炼信号**

- 候选模型：合法性是协议外部但决定协议能否执行的硬约束。
- 候选模型：去中心化不是“没有权力”，而是权力之间有制衡、用户有退出通道、规则有可验证性。
- 决策启发式：治理设计先看谁能退出、谁能否决、谁能串谋，而不是先看票数。

### 2.4 货币、代币、机制设计与公共品线

**核心样本**

- `002_What in the information finance era is even a medium of exchange.txt`
- `008_What else could memecoins be.txt`
- `017_What in the world is “Bitcoin maximalism”, anyway.txt`
- `018_On path dependence, market-makers and stablecoins.txt`
- `041_What “low risk” in DeFi should actually mean.txt`
- `042_Decentralized protocol monetization and forks.txt`
- `043_Metcalfe’s law, network effects and crypto systems.txt`
- `055_A note on charity.txt`
- `060_The futures of money, part 1.txt` 到 `065_The futures of money, part 6.txt`
- `066_Gas pricing and mechanism analysis.txt`
- `067_Quadratic funding, Gitcoin and public goods.txt`
- `080_Gini, inequality and crypto governance.txt`
- [一手] `Low-risk defi can be for Ethereum what search was for Google`, 2025-09-21, https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html

**观察**

- [一手] Vitalik 对货币和代币的典型写法不是“币种最大化”，而是拆网络效应、流动性、激励、单位记账、稳定性和公共品外部性。
- [一手] `Quadratic funding`、`Gitcoin` 和 `A note on charity` 显示他把资金分配当成机制设计，而不是纯慈善情绪。
- [一手] 2025 年 low-risk DeFi 文本把 DeFi 从投机叙事中重新筛选，寻找更低风险、更像基础服务的使用场景。

**可提炼信号**

- 候选模型：代币是协调和激励工具，不是终点。
- 候选模型：机制设计优先于道德喊话；先改激励和信息结构，再期待行为改变。
- 张力：Ethereum 不想只是金融赌场，但实际收入、用户需求和应用成熟度可能反而来自更低风险的金融用例。

### 2.5 隐私、身份、开源、AI 与可验证性线

**核心样本**

- `022_Why I support privacy.txt`
- `023_Why I support open source and copyleft.txt`
- `024_Why I’m not a cypherpunk.txt`
- `025_Only open source can make AI aligned.txt`
- `026_Why openness and verifiability matter for the future of science and technology.txt`
- `053_AI, humans and the edges of agency.txt`
- `054_Against biometric identity maximalism.txt`
- `056_The backpack problem of digital identity.txt`
- `081_Garbled circuits and privacy-preserving computation.txt`
- `098_ZK API Usage Credits LLMs and Beyond.txt`
- [一手] `Why I used to prefer permissive licenses and now favor copyleft`, 2025-07-07, https://vitalikblog.w3eth.io/general/2025/07/07/copyleft.html
- [一手] `My response to AI 2027`, 2025-07-10, https://vitalikblog.w3eth.io/general/2025/07/10/2027.html
- [一手] `I support it only if it's open source`, 2025-08-12, https://vitalikblog.w3eth.io/general/2025/08/12/onlyopensource.html
- [一手] `The importance of full-stack openness and verifiability`, 2025-09-24, https://vitalikblog.w3eth.io/general/2025/09/24/openness_and_verifiability.html
- [一手] `My self-sovereign / local / private / secure LLM setup`, 2026-04-02, https://vitalikblog.w3eth.io/general/2026/04/02/secure_llms.html

**观察**

- [一手] `The importance of full-stack openness and verifiability` 的关键扩展是：互联网已经成为现实生活，因此开放和可验证性不能只停留在软件层，而要扩展到硬件、生物技术、AI、甚至未来脑机接口。
- [一手] 2025 年 copyleft / open-source 相关文章显示他从早期更偏 permissive license，转向更重视 copyleft 或更强开放约束，这是一处真实观点演化。
- [一手] AI 2027 回应和 2026 本地安全 LLM 设置说明，他不是只停留在 AI 哲学讨论，而在把 d/acc 落到个人安全架构：本地推理、沙箱、人类确认、隐私网络、ZK API、TEE / FHE 等防御组合。

**可提炼信号**

- 候选模型：开放和可验证性是安全条件，不只是价值姿态。
- 候选模型：防御性加速不是“让一切更快”，而是让防御能力、验证能力和退出能力更快扩散。
- 张力：开源能降低门卫权力，也可能扩散滥用能力；Vitalik 的回答不是简单开/关，而是比较攻防不对称和验证条件。

### 2.6 密码学、证明系统与“把复杂性变得可证”

**核心样本**

- `013_A Philosophy of Blockchain Validation.txt`
- `057_Binius and the future of proof systems.txt`
- `058_Circle STARKs and proof engineering.txt`
- `068_GKR proofs and practical scalability.txt`
- `069_Halo proofs and recursive verification.txt`
- `070_Homomorphic ideas and encrypted computation.txt`
- `073_CBC Casper and consensus intuition.txt`
- `079_FFT intuition for cryptography.txt`
- `081_Garbled circuits and privacy-preserving computation.txt`
- `096_Explanation of DAICOs.txt`
- `097_On-chain scaling to potentially ~500 txsec through mass tx validation.txt`
- `098_ZK API Usage Credits LLMs and Beyond.txt`

**观察**

- [一手] Vitalik 对证明系统的兴趣不是纯数学审美，而是把它们当作系统边界工具：让更多执行、隐私或身份判断能在不暴露全部内部状态的情况下被验证。
- [一手] 从 `Slasher` 到 `Binius` / `Circle STARKs` / `ZK API Usage Credits`，他的证明系统写作始终连接到实际协议设计、验证成本和安全边界。

**可提炼信号**

- 候选模型：密码学是制度工程工具，用来改变“必须信任谁”的结构。
- 决策启发式：能用 proof 替代 gatekeeper 时，优先考虑 proof；但 proof 的可用性、可理解性和实现复杂度也必须计算。

## 3. 反复出现的候选心智模型

### 模型 A：可验证性优先于信任

- [一手证据] Ethereum whitepaper、`A Philosophy of Blockchain Validation`、`Why openness and verifiability matter...`、`ZK API Usage Credits`、2025-09-24 `Full-stack openness and verifiability`。
- [跨域复现] 区块链验证、AI / API、科学与生物技术、身份、硬件、未来 BCI。
- [生成力] 面对新系统，他会先问“用户或公众能否验证它没有作恶？”而不是先问“它是否承诺做好事？”
- [局限] 可验证性可能提升专家门槛；不是所有社会判断都能形式化为 proof。

### 模型 B：复杂性必须有位置

- [一手证据] `Do not overload the consensus layer`、`Encapsulated vs systemic complexity`、`Simplifying the L1`、rollup stage 文章。
- [跨域复现] L1/L2 设计、EVM 简化、governance、身份系统、AI agent 安全架构。
- [生成力] 面对新功能，他会问“这应该在核心层、边缘层、应用层还是社会层？”
- [局限] 过度模块化会造成 UX 碎片化、跨层风险和用户责任过重。

### 模型 C：去中心化 = 退出权 + 制衡 + 验证

- [一手证据] `Control as a liability`、`Balance of power`、`The near and mid-term future...decentralization`、`Moving beyond coin voting governance`。
- [跨域复现] Ethereum 路线图、DAO 治理、身份系统、AI 平台、政府/企业/群体权力。
- [生成力] 他不会满足于“节点很多”或“投票很多”，而会追问是否存在事实门卫。
- [局限] 危机中完全弱控制可能导致行动迟缓；现实组织仍需要协调中心。

### 模型 D：合法性是硬约束

- [一手证据] `The Most Important Scarce Resource is Legitimacy`、DAO hard fork 后文章、公共品和治理系列。
- [跨域复现] 硬分叉、基金会决策、DAO、公共品资助、城市治理、社区路线图。
- [生成力] 面对升级或分配问题，他会问“这套过程为什么会被接受？”
- [局限] 合法性容易被叙事和软权力捕获，无法完全形式化。

### 模型 E：机制设计优先于情绪判断

- [一手证据] `The futures of money` 系列、`Memecoins`、`Bitcoin maximalism`、`Quadratic funding`、`Low-risk DeFi`。
- [跨域复现] 代币、稳定币、公共品、治理投票、DeFi、平台网络效应。
- [生成力] 面对“这东西好不好”，他会拆成激励、流动性、外部性、串谋、退出和长期均衡。
- [局限] 机制视角会低估不可调和的价值冲突和情绪动员。

### 模型 F：防御性能力扩散

- [一手证据] `My techno-optimism` / d/acc、`"I support it only if it's open source" should be a more common viewpoint`、`My response to AI 2027`、2026-04-02 安全 LLM 设置；本地摘要 `025_Only open source can make AI aligned.txt` 只作索引。
- [跨域复现] AI、网络安全、生物防御、信息防御、隐私技术、开源硬件/软件。
- [生成力] 面对危险技术，他会优先寻找开放、可验证、可复制、可本地运行的防御方案，而不是只靠封闭门卫。
- [局限] 防御扩散和攻击扩散会同时发生，不能把开源浪漫化。

## 4. 决策启发式候选

1. 如果一个功能会增加共识层复杂度，默认拒绝，除非它能显著降低系统性风险。
2. 如果一个方案提高效率但降低退出权，要把退出权损失当成真实成本。
3. 如果一个治理机制只靠 coin voting，要检查鲸鱼、投票冷漠、串谋和合法性缺口。
4. 如果一个身份系统追求“一人一 ID”，要检查伪匿名、胁迫、错误恢复和多身份上下文。
5. 如果一个 AI / 生物 / 硬件系统要成为现实生活基础设施，要求全栈开放和可验证性。
6. 如果一个 DeFi / memecoin / 代币用例看起来只是投机，要寻找能否转化为低风险、正和或公共品导向。
7. 如果一个复杂路线图开始自洽得过头，要警惕 galaxy-brain narrative overfitting。
8. 如果一个问题可以通过 proof、audit、open source 或 local execution 减少信任，优先考虑这些路径。
9. 如果一个系统依赖少数门卫“善意”，先建模门卫失效、作恶或被捕获时会发生什么。
10. 如果短期兼容性和长期简洁性冲突，至少计算一次“大迁移换大简化”的可能性，而不是无穷 patch。

## 5. 重要张力

- 去中心化理想 vs Vitalik 本人和 Ethereum Foundation 的事实软权力。
- L2 多样性和文化扩展 vs 统一用户体验与跨链安全。
- 开源 / copyleft / full-stack openness vs 滥用风险和商业激励。
- 低风险 DeFi 作为 Ethereum 经济支柱 vs crypto 的非金融社会理想。
- L1 简化 vs EVM 兼容性和生态迁移成本。
- 隐私与伪匿名 vs 反女巫、反滥用和公共安全。
- 防御性加速 vs 技术扩散带来的攻击面扩张。

## 6. 智识谱系

### 6.1 直接可见来源

- [一手] Bitcoin / Satoshi 系统：Ethereum whitepaper 以 Bitcoin 为起点。
- [一手] Wei Dai、Hal Finney 等早期加密货币前史：Ethereum whitepaper 相关背景。
- [一手] 机制设计、经济学、政治理论：`Ideas worth stealing from economics and political theory`、`Quadratic funding`、`Gini`、`Concave governance`。
- [一手] 密码学和证明系统：`FFT`、`Binius`、`Circle STARKs`、`Halo`、`GKR`、`Garbled circuits`。
- [一手/近一手] `Proof of Stake` 作为本人文章合集，把早期 Ethereum、自由、治理、城市、公共品等文章重新组织成一条思想线。

### 6.2 推断谱系

[推断] Vitalik 的谱系不是单一 cypherpunk，而是：

Bitcoin / 密码朋克 / 数学竞赛式抽象能力 → Ethereum 通用协议工程 → 机制设计与公共品 → 治理与合法性 → ZK / 可验证计算 → d/acc / open-source AI / full-stack openness。

## 7. 高价值来源清单

### 一手 / 近一手来源

- Ethereum whitepaper: https://ethereum.org/en/whitepaper/
- Vitalik blog mirror / index: https://vitalikblog.w3eth.io/
- Ethereum Foundation blog: https://blog.ethereum.org/
- Ethereum Research: https://ethresear.ch/
- `Proof of Stake` book page: https://sevenstories.com/books/4443-proof-of-stake
- `Scaling Ethereum L1 and L2s in 2025 and beyond`: https://vitalikblog.w3eth.io/general/2025/01/23/l1l2future.html
- `Simplifying the L1`: https://vitalikblog.w3eth.io/general/2025/05/03/simplel1.html
- `The math of when stage 1 and stage 2 make sense`: https://vitalikblog.w3eth.io/general/2025/05/06/stages.html
- `Why I used to prefer permissive licenses and now favor copyleft`: https://vitalikblog.w3eth.io/general/2025/07/07/copyleft.html
- `My response to AI 2027`: https://vitalikblog.w3eth.io/general/2025/07/10/2027.html
- `The importance of full-stack openness and verifiability`: https://vitalikblog.w3eth.io/general/2025/09/24/openness_and_verifiability.html
- `Low-risk defi can be for Ethereum what search was for Google`: https://vitalikblog.w3eth.io/general/2025/09/21/low_risk_defi.html
- `Balance of power`: https://vitalikblog.w3eth.io/general/2025/12/30/balance_of_power.html
- `My self-sovereign / local / private / secure LLM setup`: https://vitalikblog.w3eth.io/general/2026/04/02/secure_llms.html

### 本地摘要包

- `local-vitalik_100_txt/README.txt`
- `local-vitalik_100_txt/001_...txt` 到 `local-vitalik_100_txt/100_...txt`

## 8. 诚实边界

- 本地 100 txt 是摘要包，不是逐字稿；本文件把它作为主题地图和来源索引，而不是原文引用依据。
- `vitalikblog.w3eth.io` 是公开镜像，最终如需更高精度，应与 `github.com/vbuterin/blog` 原始仓库逐篇核对。
- 本文件关注“著作与系统性写作”，不覆盖所有 X 碎片发言，也不覆盖所有会议视频。
- 对 2026-04-07 之后的新文章和访谈未覆盖。

## 9. 可直接供最终 Skill 使用的提炼

如果最终 Skill 只能保留一句话，建议是：

> Vitalik 的核心视角是：把技术系统看成权力、验证、退出、复杂性和合法性共同构成的社会技术协议；好的设计不是单点最优，而是在长期风险下维持可验证、可退出、可协作、可防御的开放秩序。
