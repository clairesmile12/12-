# 经营学顶刊论文蒸馏插件

版本 3.0.0。用于管理学与经营学论文精读、论证与方法核查、写作动作学习和草稿修订。

## 使用入口

本插件的 skill 位于 [skills/business-paper-distiller/SKILL.md](skills/business-paper-distiller/SKILL.md)。按任务读取其中链接的 references，不能只读取说明首页就声称完成全部分析。

### 已安装 skill

上传论文全文后输入：

```text
请使用 business-paper-distiller，分析这篇论文的研究问题、理论贡献、分析思维与框架结构；逐段拆解引言和假设推导。区分原文明确、文本重构和迁移假设，并提供实际页码或段落依据。
```

当前支持显式 skill 语法的 Codex 环境也可输入 `$business-paper-distiller`。

### 从 GitHub 读取后使用

在已连接且有仓库访问权限的 GitHub 工具环境中，选择 GitHub 后发送：

```text
请读取 clairesmile12/12- 仓库 main 分支中的 plugins/business-paper-distiller/skills/business-paper-distiller/SKILL.md，并按本次任务读取它链接的 references。依照这套经营学论文蒸馏流程，分析我上传的论文，重点学习引言、理论机制和贡献论证。读不到文件时请明确说明。
```

这属于读取工作流程并用于本次任务，不等于安装插件；只提及 GitHub 也不保证自动发现整个 skill。提供准确路径更可靠。

### 在另一台设备安装独立 skill

在支持 Skill Installer 的 Codex 环境发送：

```text
请使用 skill-installer 从以下目录安装 business-paper-distiller：
https://github.com/clairesmile12/12-/tree/main/plugins/business-paper-distiller/skills/business-paper-distiller
```

插件清单位于 `.codex-plugin/plugin.json`；仓库插件目录入口位于根目录 `.agents/plugins/marketplace.json`。保存源码不等于已安装插件或已发布到公共插件目录。只需一份启用的 skill，避免并行维护多个副本造成版本混淆。

## 分析范围

- 定量实证全文：论证与证据、思维动作、逐段写作三层拆解及六项核查。
- 多篇比较：至少三篇可比论文后归纳样本内规律，不宣称代表整个期刊。
- 草稿修订：保留事实、引文与证据强度，交付实际修改和待补证据。
- 摘要或单独章节：限当前可见材料；非定量研究限结构与写作初读。

不生成虚构结果、引文或作者心理历程，不执行原始数据估计。结构校验通过不代表完整行为评测通过。既有实测与定向走查不构成盲评或留出集验证。

## 来源与授权

详见 [来源与取舍](skills/business-paper-distiller/references/source-notes.md)。本包未附论文原文或用户私人稿件，也未为整包指定开源许可；公开可见不等于授予任意再分发许可。

官方说明：[Build skills](https://learn.chatgpt.com/docs/build-skills)。
