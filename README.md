# AI Animation Skills Hub

> A practical, curated knowledge base and toolkit for AI-assisted animation and video production.
>
> 面向 AI 动画与视频创作的实战型 Skills、工具、模型、工作流与制作规范知识库。

**Status / 状态:** Initial foundation  
**Languages / 语言:** 简体中文为主，关键文档提供 English  
**Scope / 范围:** Agent Skills · AI Video · 2D/3D Animation · Character Animation · Storyboarding · Motion Graphics · Lip Sync · Editing · Voice & Sound · VFX

## 1. 项目目标 | Mission

本项目旨在建立一个可持续维护、可验证、可复用的 AI Animation Skills Hub，帮助创作者和 AI Agent 完成从创意、前期策划到生成、动画、声音、剪辑和交付的完整制作流程。

This repository aims to be a maintainable, verifiable, reusable hub for AI-assisted animation production—from ideation and pre-production to generation, animation, sound, editing, and delivery.

核心原则：

- **可执行优先**：优先收录有明确输入、步骤、输出和验收标准的实战内容。
- **分类准确**：严格区分 Agent Skill、模型、软件工具、插件/节点和工作流。
- **来源可追溯**：记录官方来源、版本、许可证和最后核验日期。
- **安全合规**：尊重上游许可证、模型使用条款、肖像/声音权利和内容政策。
- **持续更新**：标记维护状态、兼容性和已知限制，不把过时内容伪装成当前推荐。

## 2. 内容分类 | What belongs here

| 类型 | 定义 | 收录要求 |
|---|---|---|
| Agent Skill | 可供 Agent 按说明执行的技能包 | 必须有真实的 `SKILL.md`，并注明来源/许可证 |
| Model | 视频、图像、语音、动作等模型 | 标注官方地址、版本/发布日期、许可与硬件要求 |
| Tool | 独立软件或服务 | 标注用途、平台、官方文档与状态 |
| Node / Plugin | ComfyUI 等平台的扩展节点或插件 | 标注宿主平台、安装方式、依赖和兼容性 |
| Workflow | 多工具组合的可复现流程 | 标注步骤、输入输出、参数和失败处理 |
| Reference | 规范、术语、制作方法与研究资料 | 标注来源和适用范围 |

**重要：** 一个模型、插件或普通教程不会因为被称为“skill”就自动成为 Agent Skill。只有包含可验证技能指令文件的项目，才会归入 Agent Skills。

## 3. 覆盖领域 | Production map

- **Pre-production / 前期制作**：创意开发、剧本、世界观、角色设定、分镜、镜头表、视觉开发。
- **AI image & video / 图像与视频生成**：文生图、图生视频、视频续写、镜头控制、风格一致性。
- **Character animation / 角色动画**：角色绑定、动作生成、动作迁移、表情与姿态控制。
- **2D & 3D animation / 二维与三维动画**：传统 2D、程序化动画、Blender 场景与动画。
- **Motion graphics / MG 动画**：动态图形、标题、信息可视化、品牌动画。
- **Lip sync / 口型同步**：语音驱动口型、面部动画、说话人一致性。
- **Editing / 自动剪辑**：镜头筛选、节奏、转场、字幕、合成与导出。
- **Voice & sound / 配音与音效**：TTS、配音流程、音乐、拟音、音频清理与混音。
- **VFX / 特效**：抠像、跟踪、粒子、合成、修复与增强。
- **Delivery / 交付**：质量检查、格式、字幕、版权和归档。

## 4. Repository map / 仓库结构

```text
.
├── skills/                 # Verified Agent Skills (each has SKILL.md)
├── catalog/                # Models, tools, nodes and skill index
├── workflows/              # End-to-end reproducible production workflows
├── templates/              # Reusable production and skill templates
├── docs/                   # Taxonomy, installation, compatibility, licensing
├── research/               # Evaluations and source-backed research notes
├── .github/                # Contribution and issue templates
├── CONTRIBUTING.md
├── ROADMAP.md
└── README.md
```

目录会随着内容增长逐步建立；不会为了填满目录而创建未经验证的条目。

## 5. 快速开始 | Getting started

1. 从 [内容分类](docs/taxonomy.md) 了解本项目的收录标准。
2. 用 [Skill 模板](templates/skill-template/SKILL.md) 创建新的 Agent Skill。
3. 提交前阅读 [贡献指南](CONTRIBUTING.md) 和 [许可证说明](docs/licensing.md)。
4. 通过 [路线图](ROADMAP.md) 查看建设优先级。

目前仓库处于基础框架阶段，具体工具、模型和 Skill 将在核验官方来源、许可和维护状态后逐步收录。

## 6. 收录质量标准 | Curation checklist

每个条目尽可能记录：

- 名称、类型、用途和适用制作阶段
- 官方仓库/网站/文档链接
- 上游维护者与当前维护状态
- 版本、发布日期或最后核验日期
- 许可证、商业使用限制及模型使用条款
- 安装/运行要求、依赖与兼容性
- 最小可复现示例、输入输出和已知限制
- 适合的工作流，以及不适合的场景

## 7. 免责声明 | Disclaimer

本项目是社区知识整理与工作流研究项目，不代表任何模型、软件或服务的官方立场。上游项目的名称、商标、代码、模型权重和文档归其各自权利人所有。使用前请阅读对应上游许可和服务条款。

---

**欢迎参与。** 请通过 Issue 提交建议，或阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 参与维护。
