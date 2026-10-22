# 设计来源与整合边界

整理日期：2026-10-23。版本：3.0.0。主体由用户初始技能、SKILL.pdf、EVAL PLAN.pdf 和实际试读反馈演化而来。本版独立编写操作指令与模板，没有整包复制、安装或执行下列仓库的代码；没有把其文档当成高于用户要求的指令。

## 来源与取舍

| 来源 | 查看位置／材料 | 参考的设计思想 | 本版没有采用的部分 |
|---|---|---|---|
| 用户原版 | 三层拆解、六项核对、迁移规则、评测方案 | 作为核心结构，保持证据三标签、摘要降级、定量深读边界 | 不把已有一次试读包装为可靠性证明 |
| [MGMT-Paper-Skills](https://github.com/HaonanAlex/MGMT-Paper-Skills) | [风格技能](https://github.com/HaonanAlex/MGMT-Paper-Skills/blob/main/mgmt-paper-style-benchmark/SKILL.md)、[比较模板](https://github.com/HaonanAlex/MGMT-Paper-Skills/blob/main/mgmt-paper-style-benchmark/templates/style_benchmark_matrix.md)、writing 与 reviewer-simulation | 范文对照、稿件差距、章节功能和修订任务分离 | 固定贡献数、固定稳健性数量、把所有管理学论文写成政策研究、每角色凑严重问题 |
| [Awesome-Journal-Skills](https://github.com/brycewang-stanford/awesome-journal-skills) | AMJ contribution-framing／writing-style，SMJ theory-development，Organization Science writing-style | 理论贡献与结果区分、构念一致、分析层级与读者、期刊校准 | 未核实的投稿硬指标、固定段落顺序、把真实局限仅重新包装成边界；不自动导入期刊专属断言 |
| [K-Dense Scientific Critical Thinking](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-critical-thinking) | SKILL.md 的证据评估流程与参考资料组织 | 先定位证据再评价，区分报告缺失与未执行，按结论受影响程度提出补证 | 医学 GRADE／RoB 工具不直接套到管理学，不加入绘图 API 依赖 |
| [Scientific Writing Skills](https://github.com/dvdsosa/scientific-writing-skills) | sciwrite-manuscript、README 的脚本与示例说明 | 章节的读者任务、术语及数字保真、可执行写作示例 | 不导入“引言超过五段就是综述”等绝对规则；没有移植或声称运行其审计脚本 |
| [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) | academic-paper-reviewer 与 evals/README.md | 用于对比证据定位和评测基础设施的成熟度 | 不复制其非商业许可指令、模板或代码，不引入多代理流程，不将其评测设施等同已验证效果 |

已阅第三方模块的许可标识包括 Apache-2.0（MGMT）、MIT（Awesome Journal、Scientific Writing、K-Dense 相应技能）及 CC BY-NC 4.0（Academic Research Skills 根许可证）。这些是来源标识，不是本技能整体许可声明。本包没有代用户选择公开发布许可证。未来若复制第三方原文或代码，应重新核对具体文件许可并保留所需声明；本次没有将第三方文本或脚本作为组成文件分发。

## 本次读取的期刊模块定位

- [AMJ 贡献](https://github.com/brycewang-stanford/awesome-journal-skills/blob/main/Academy-of-Management-Journal-Skills/skills/amj-contribution-framing/SKILL.md)。以链接与查阅日期标识来源，不声称这些可变链接是固定快照。
- [AMJ 写作](https://github.com/brycewang-stanford/awesome-journal-skills/blob/main/Academy-of-Management-Journal-Skills/skills/amj-writing-style/SKILL.md)。
- [SMJ 理论](https://github.com/brycewang-stanford/awesome-journal-skills/blob/main/Strategic-Management-Journal-Skills/skills/smj-theory-development/SKILL.md)。
- [Organization Science 写作](https://github.com/brycewang-stanford/awesome-journal-skills/blob/main/Organization-Science-Skills/skills/orgsci-writing-style/SKILL.md)。

## 官方来源优先于第三方概括

期刊档案内记录了 AOM、SMS 与 INFORMS 的官方入口。2026-10-23 查阅时，SMJ 官方介绍接受 verbal theory 等多种方法；这与所读第三方模块对纯概念文章的绝对排除不一致，因此不采纳后者。Organization Science 官方声明强调多种贡献形式，也不能简化为只有理论新颖性或因果识别才有价值。

本版从这些来源抽取可执行的分析问题，再结合用户证据要求重新组织。没有依据 Stars、宣称用户量或代码测试数量给任何项目作效果排名。
