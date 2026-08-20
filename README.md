# TC-Writing-style

A Codex skill for drafting, revising, and reviewing applied transportation and low-altitude mobility papers.

适用于出行行为、交通需求预测、交通规划、UAM/eVTOL、GIS、基础设施选址、调查与计量分析、多目标优化及实证案例研究。它强调从真实交通决策问题出发，将数据、方法、发现与规划或政策含义连接起来，而不是默认采用计算机论文常见的“任务—模型—benchmark”叙事。

## Main features

- Routes writing by research mode: travel behavior and demand, planning and infrastructure, or emerging low-altitude mobility.
- Provides section-specific guidance for the abstract, introduction, literature review, methods, results, discussion, and conclusion.
- Distinguishes observed, estimated, calibrated, borrowed, expert-assigned, and scenario-based quantities.
- Adds an assumption ledger for prospective UAM/eVTOL and parameterized planning studies.
- Includes a reviewer-facing checklist for evidence, transport meaning, spatial impacts, planning use, and transferability.
- Asks once per use whether format checking is needed, avoiding unnecessary format-analysis tokens.
- Supports either a location-specific compliance report or automatic formatting of a safe manuscript copy, based on `【定稿】英文投稿模板.docx`.

## Repository structure

```text
TC-Writing-style/
|-- SKILL.md
`-- references/
    |-- narrative-logic.md
    |-- abstract-introduction.md
    |-- literature-review.md
    |-- study-design-methods.md
    |-- results-discussion.md
    |-- conclusion-policy.md
    |-- domain-review.md
    `-- submission-format.md
```

## Installation

Clone the repository into the Codex skills directory:

```bash
git clone https://github.com/GuYuan-1024/TC-Writing-style.git ~/.codex/skills/tc-writing-style
```

The valid Codex skill identifier is `tc-writing-style`; the UI display name is `TC-Writing-style`.

## Reference papers

The narrative guidance was synthesized from the following papers as writing-logic references rather than text templates:

- Tang, L., Ho, C. Q., Hensher, D. A., & Zhang, X. (2022). Investigating traveller's overall information needs: What, when and how much is required by urban residents. *Travel Behaviour and Society*, 28, 155-169. https://doi.org/10.1016/j.tbs.2022.03.006
- Tang, L., et al. (2026). City Fly: Modeling demand and vertiport location jointly for urban commuting. *Travel Behaviour and Society*, 42, 101142. https://doi.org/10.1016/j.tbs.2025.101142
