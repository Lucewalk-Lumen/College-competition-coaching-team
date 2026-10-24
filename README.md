# college-competition-coaching-team

**大学生赛事教练团** · v1.0.0 · `team`

> Coaching team for college student competitions — planning, mentoring and stage-gate review


Part of the [Lucewalk Lumen](https://github.com/Lucewalk-Lumen/about-me) collection.


## What it does

- **Planner** — breaks the competition timeline into stage-gated milestones
- **Optimizer** — iterates the submission materials round by round
- **Collator** — consolidates inputs from the student team into one coherent package
- **Reviewer** — independent stage-gate review before each submission

## How it works

- A stage-gate pipeline: plan → draft → optimize → collate → review, one gate per submission round
- A shared competition knowledge base (`competition-kb`) keeps past cases and judging criteria

## Agent roster

| Agent | Role |
|---|---|
| `ccc-collator` | 资料整合师 · 路衡 |
| `ccc-optimizer` | 文本打磨师 · 计程 |
| `ccc-planner` | 选题规划师 · 苏理 |
| `ccc-reviewer` | 评审答辩教练 · 优然 |
| `ccc-team-lead` | 大学生赛事教练团 · 主理教练 |

## Skills

`competition-kb`

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk-Lumen/college-competition-coaching-team/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v1.0.0**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).


---

## How to use / 如何使用

This is an **expert package / skill for the WorkBuddy AI assistant**.

**Prerequisites · 前置条件**
- WorkBuddy installed and signed in (latest version recommended).
- Prepare your own materials first (e.g. your literature library / course outline) — the agent works under a "stay faithful to the source, cite the page" rule.

**Import / enable · 导入 / 启用**
1. Download the package zip from this repo's **Releases**, or clone the repo; keep the `.codebuddy-plugin/` manifest intact.
2. In WorkBuddy, *custom connector → trust & enable*, or import the expert / enable the skill from the skill center.
3. Run one minimal example below to confirm the output matches your standards.

**Minimal example · 最小示例**
> 给我们的参赛项目做阶段性评审与改进建议。

**More · 更多**
Full onboarding & per-line guidance: portal [Lucewalk Lumen · 沐光行客](https://github.com/Lucewalk-Lumen/about-me) → "How to use". Issues: open one on this repo.

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# 大学生赛事教练团

**大学生赛事教练团:规划、辅导与提交前评审的阶段门禁流水线**

- 版本:v1.0.0 · 类型:team
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[Lucewalk Experts 门户](https://github.com/Lucewalk-Lumen/about-me)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk-Lumen/college-competition-coaching-team/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
