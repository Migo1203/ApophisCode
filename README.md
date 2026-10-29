# ApophisCode 新媒体增长与市场研究

本项目面向 ApophisCode 的中国大陆市场，目标是在真实产品研究和数据验证的基础上，逐步建立可执行的新媒体获客体系，关注注册、首次 API 调用和付费等环节。

项目负责人提供的官网是 [https://apophis.uk/](https://apophis.uk/)。目前关于产品定位、支持的模型、接口兼容性、价格及服务能力的描述均为**待验证信息**；本次初始化未核查官网，也未开展市场研究。

## 项目结构

```text
.
├── AGENTS.md                  # 本仓库长期协作规范
├── ROADMAP.md                 # 五个阶段及完成标准
├── docs/                      # 已验证的知识与各领域研究框架
│   ├── product.md             # 产品研究
│   ├── market.md              # 行业与用户研究
│   ├── competitors.md         # 竞品比较
│   ├── compliance.md          # 法规与平台规则研究
│   └── growth.md              # 品牌、内容与增长分析
├── research/                  # 研究过程与来源
│   ├── source-index.md        # 来源索引
│   └── competitors/README.md  # 竞品调查记录索引
├── templates/                 # 可复制使用的研究和复盘模板
├── tasks/                     # 进度、待提供资料、问题与决策
└── .gitignore                 # 常见本地敏感文件的忽略规则
```

## 如何使用

1. 从 [当前任务](tasks/current.md) 和 [路线图](ROADMAP.md)了解状态与下一步。阶段顺序用于组织工作，具体范围和优先级由项目负责人决定。
2. 研究时复制 [产品分析](templates/product-analysis.md)、[竞品分析](templates/competitor-analysis.md)、[内容分析](templates/content-analysis.md)或[运营复盘](templates/retrospective.md)模板，按实际需要保存到 `research/`；经核实且适合复用的结论再整理到 `docs/`。
3. 在 [来源索引](research/source-index.md)登记证据，记录链接、核查日期和适用范围；在 [问题与决策](tasks/questions-and-decisions.md)记录未解决问题和负责人作出的关键决定。
4. 对外发布、重要定位和敏感商业决策交由项目负责人最终决定。任何未经证实的信息都不得作为产品事实或宣传承诺。

初始化之后，优先开展的研究是：**收集并核验 ApophisCode 的官方产品资料，梳理从注册到首次 API 调用的产品路径**。先做证据盘点和流程梳理；真实账号操作、实际调用和费用支出需先明确授权与预算。

## 协作与数据安全

默认使用简体中文，技术名称保留英文。事实、推断、假设与建议分开标记；无法核验的内容标为「待验证」。不得在仓库中保存真实 API Key、密码、客户个人信息或其他敏感数据。`.gitignore` 只能减少误提交，不能替代提交前检查。

下一阶段需要的资料见 [待提供的产品资料](tasks/inputs-needed.md)。本仓库保存研究框架与经过处理的证据，不要求提交账号凭据或原始客户数据。
