# v2 Provenance Manifest

调研时间：2026-04-07

本版本按女娲流程重新执行，使用 6 个 `gpt-5.4`、`reasoning_effort=xhigh` 子 agent 分别沉淀 6 个研究维度；未使用 mini 模型生成研究文件。

## 子 Agent 分工

| 文件 | 维度 | 模型 | 推理配置 | 输入范围 |
|---|---|---|---|---|
| `references/research/01-writings.md` | 本人长文与系统写作 | `gpt-5.4` | `xhigh` | Vitalik 博客、Ethereum whitepaper、Ethereum Foundation、Ethereum Research、`Proof of Stake` 书籍信息、`references/sources/local-vitalik_100_txt/` |
| `references/research/02-conversations.md` | 长访谈与即兴思考 | `gpt-5.4` | `xhigh` | 80,000 Hours、Bankless、Lex、TIME、Reddit AMA、Foresight 经 Bankless 二手摘要、`references/sources/local-vitalik_100_txt/` |
| `references/research/03-expression-dna.md` | 表达 DNA | `gpt-5.4` | `xhigh` | 博客标题与结构、X / 短帖风格、访谈表达、`references/sources/local-vitalik_100_txt/` |
| `references/research/04-external-views.md` | 外部视角与批评 | `gpt-5.4` | `xhigh` | TIME、WIRED、VICE、Nasdaq、Guardian、Business Insider、SSRN、De Filippi 等外部材料、`references/sources/local-vitalik_100_txt/` |
| `references/research/05-decisions.md` | 关键决策记录 | `gpt-5.4` | `xhigh` | Ethereum 创立、DAO hard fork、PoS、rollup、L1 simplification、low-risk DeFi、open-source AI、balance of power、`references/sources/local-vitalik_100_txt/` |
| `references/research/06-timeline.md` | 人物时间线 | `gpt-5.4` | `xhigh` | 1994-2026 时间线、最近 12 个月公开动态、Vitalik 博客索引、`references/sources/local-vitalik_100_txt/` |

## 本地语料

`references/sources/local-vitalik_100_txt/` 是随 v2 产物复制进来的 100 份摘要学习笔记，包含 `README.txt` 和 `001_...txt` 到 `100_...txt`。

该语料不是 Vitalik 原文逐字稿，也不是可直接引用的 transcript；它只用于主题聚类、来源索引、长期关注点识别和与公开来源交叉验证。

## 复审

v2 生成后追加了 2 个 `gpt-5.4` 只读复审 agent：

- 可用性 / 角色边界复审：检查触发范围、persona 边界、模型完整性、是否误导为 Vitalik 本人观点。
- 事实边界复审：检查一手 / 二手混淆、摘要包使用边界、本机路径和过期断言。

复审建议已用于收紧触发条件、增强非本人边界、补入本 provenance manifest、复制本地 100 txt 语料包，并修正失效镜像链接。
