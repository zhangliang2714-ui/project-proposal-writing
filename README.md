# 项目书写作

按项目类别起草、修改和诊断中文科研项目书的 Codex skill。显示名称为 **项目书写作**，调用名称为 `$project-proposal-writing`。

## 能做什么

- 区分面上、青年、重点、人才、联合基金、国际合作、重点研发、应用转化与阶段报告的论证任务。
- 优化背景、现状、科学问题、研究内容、方案、创新及前期基础，保留事实与修改边界。
- 从具体场景与材料瓶颈引出设计路线；包含高熵陶瓷纤维防火隔热示例。
- 按需调用合成、力学、催化和热防护规则，检查因果、性能条件与科学层级。

## 安装

将本仓库克隆到个人 Codex skills 目录下的 `project-proposal-writing` 文件夹。目标目录已存在时，先备份再合并更新，不直接覆盖个人修改。

Windows PowerShell：

```powershell
git clone https://github.com/zhangliang2714-ui/project-proposal-writing.git "$env:USERPROFILE/.codex/skills/project-proposal-writing"
```

macOS / Linux：

```sh
git clone https://github.com/zhangliang2714-ui/project-proposal-writing.git ~/.codex/skills/project-proposal-writing
```

如自定义了 `CODEX_HOME`，将仓库放在其 `skills/project-proposal-writing` 目录。安装后在新对话中调用；也可下载仓库 ZIP，解压并将文件夹命名为 `project-proposal-writing`，确保 `SKILL.md` 位于文件夹根部。

## 使用示例

```text
使用 $project-proposal-writing，按面上项目的风格优化以下立项依据。
先诊断需求、研究现状与科学问题之间的衔接，再给可替换正文。
保留全部数字和引文，不增加未经提供的前期结果。
```

```text
使用 $project-proposal-writing，写一段高熵氧化物陶瓷纤维用于防火隔热的背景。
从公共安全需求落到材料要求，再自然引出高熵设计。
未提供具体组成和实验数据，不编造性能指标。
```

```text
使用 $project-proposal-writing，只把下面一句中的“同时”改成“并行”，其他内容不动。
```

## 主要内容

| 内容 | 入口 |
|---|---|
| 技能工作方式 | [SKILL.md](SKILL.md) |
| 项目分类 | [项目类型](references/project-types.md) |
| 语言与逻辑 | [风格规则](references/style-guide.md)、[论证方法](references/narrative-moves.md) |
| 国家需求与章节衔接 | [章节写法](references/section-playbook.md) |
| 防火隔热 | [热防护规则](references/thermal-protection-playbook.md)、[背景示例](examples/high-entropy-fire-insulation.md) |
| 学习来源与适用边界 | [匿名来源说明](references/source-scope.md) |

## 公开内容与适用范围

本仓库发布写作规则和原创示例，原始项目书及详细本地阅读档案不随仓库发布。规则的样本基础主要来自材料与纤维方向；青年科学基金、博士后等缺完整直接范本，相关建议需结合当前指南使用。示例不替代文献核验，也不提供获批保证。
