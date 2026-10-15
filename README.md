# CUMT Alethic Insight Lab Public Governance · 公开治理文档

[English](README.en.md) · [简体中文](README.zh-CN.md)

Public governance documents for CUMT Alethic Insight Lab, for members, applicants, collaborators, and future student maintainers.

本仓库用于存放 CUMT Alethic Insight Lab 面向公众的治理文档，面向成员、申请者、合作者和未来学生维护者。

Boundary: this repository only holds public-facing governance documents; internal processes live in the private `internal-governance` repository, and infrastructure handoff lives in the private `infra-handoff` repository.

边界：本仓只管面向公众的治理文档；内部流程归 `internal-governance`（私有）、基础设施归 `infra-handoff`（私有）。

## Documents · 文档索引

| Document 文档 | Description 说明 |
| --- | --- |
| [Charter](docs/en/charter.md) / [章程](docs/zh-CN/charter.md) | What the lab is: mission, scope, and operating principles. 实验室的定位、使命、方向与基本原则。 |
| [Membership](docs/en/membership.md) / [成员规则](docs/zh-CN/membership.md) | Member types, expectations, and access rules. 成员类型、行为期望与访问权限。 |
| [Project Governance](docs/en/project-governance.md) / [项目治理](docs/zh-CN/project-governance.md) | How projects start, repository rules, and maintainer duties. 如何立项、仓库规则与维护者职责。 |
| [Open-Source Policy](docs/en/open-source-policy.md) / [开源政策](docs/zh-CN/open-source-policy.md) | Issue-first workflow and practices to avoid. Issue 优先的协作流程与应避免的做法。 |
| [AI Assistance Policy](docs/en/ai-assistance-policy.md) / [AI 辅助使用规则](docs/zh-CN/ai-assistance-policy.md) | Disclosure, verification, and testing requirements for AI-assisted work. AI 辅助贡献的披露、核验与测试要求。 |
| [Release Policy](docs/en/release-policy.md) / [发布规范](docs/zh-CN/release-policy.md) | Semantic versioning and release-note requirements. 语义化版本与发布说明要求。 |
| [Review Policy](docs/en/review-policy.md) / [Review 规则](docs/zh-CN/review-policy.md) | What reviewers check and what contributors should do. Review 者的检查项与贡献者的配合事项。 |

## Repository Defaults · 仓库默认约定

| Item 事项 | Default 默认 |
| --- | --- |
| Code license 代码许可 | MIT（见 project-template 的 LICENSE） |
| Content license 内容许可 | 文档/教程 CC-BY-4.0；资源清单 CC0 |
| CI/CD | 不要求。练习、竞赛与大创类项目不预置 CI；内容型仓库（如 awesome-ai）可配非阻断的定期维护自动化（如每周死链巡检） |

## Sensitive Materials · 敏感材料

This public repository must not contain real recruitment questions, interview records, scoring rubrics, candidate evaluations, credentials, tokens, recovery codes, private datasets, unreleased checkpoints, or internal incident records.

本公开仓库不得包含真实招新题、面试记录、评分标准、候选人评价、凭证、token、恢复码、私有数据集、未公开模型权重或内部事故记录。
