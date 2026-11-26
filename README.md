# AI Animation Skills Hub

> A practical, curated knowledge base and toolkit for AI-assisted animation and video production.
>
> 面向 AI 动画与视频创作的实战型 Skills、工具、模型、工作流与制作规范知识库。

**Status / 状态:** Active curation · 基础框架与首批资源已建立  
**Languages / 语言:** 简体中文为主，关键文档提供 English  
**Scope / 范围:** Agent Skills · AI Video · 2D/3D Animation · Character Animation · Storyboarding · Motion Graphics · Lip Sync · Editing · Voice & Sound · VFX

## 1. 项目目标 | Mission

本项目旨在建立一个可持续维护、可验证、可复用的 AI Animation Skills Hub，帮助创作者和 AI Agent 完成从创意、前期策划到生成、动画、声音、剪辑和交付的完整制作流程。

This repository aims to be a maintainable, verifiable, reusable hub for AI-assisted animation production—from ideation and pre-production to generation, animation, sound, editing, and delivery.

核心原则：可执行优先、分类准确、来源可追溯、安全合规、持续更新。

## 2. 内容分类 | What belongs here

| 类型 | 定义 | 收录要求 |
|---|---|---|
| Agent Skill | 可供 Agent 按说明执行的技能包 | 必须有真实的 `SKILL.md` |
| Model | 视频、图像、语音、动作等模型 | 官方地址、许可、版本与硬件要求 |
| Tool | 独立软件或服务 | 用途、平台、官方文档与状态 |
| Node / Plugin | 宿主软件的扩展 | 宿主版本、安装方式、依赖与兼容性 |
| Workflow | 多工具组合的制作流程 | 步骤、输入输出、参数与失败处理 |

**重要：** 模型、插件和普通教程不会因为被称为“skill”就自动成为 Agent Skill。只有包含可验证技能指令文件的项目，才会归入 Agent Skills。

## 3. 资源入口 | Resource index

### Agent Skills
- [Agent Skills 目录](catalog/agent-skills.md)
- [动画前期制作 Skill](skills/preproduction/animation-production-planner/SKILL.md)
- [角色动作制作 Skill](skills/character-animation/character-motion-production/SKILL.md)

### Models & tools
- [视频生成模型](catalog/video-models.md)
- [动画工具](catalog/animation-tools.md)
- [角色动画](catalog/character-animation.md)
- [3D 与 MG 动画](catalog/3d-and-motion-graphics.md)
- [音频工具](catalog/audio-tools.md)
- [音频与口型同步项目](catalog/audio-and-lipsync.md)

### Production workflows
- [AI 短片工作流](workflows/short-film/README.md)
- [Wan2.2 Animate + ComfyUI 角色动画](workflows/character-animation/wan2-2-animate-comfyui.md)
- [3D 动画工作流](workflows/3d-animation/README.md)
- [MG 动画工作流](workflows/motion-graphics/README.md)

### Templates & governance
- [分镜模板](templates/storyboard-template.md)
- [镜头清单 CSV](templates/shot-list-template.csv)
- [Skill 模板](templates/skill-template/SKILL.md)
- [内容分类](docs/taxonomy.md) · [许可证说明](docs/licensing.md) · [贡献指南](CONTRIBUTING.md) · [路线图](ROADMAP.md)

## 4. 收录质量标准 | Curation checklist

每个条目尽可能记录：官方来源、准确类型、版本/核验日期、代码与模型许可、依赖与兼容性、输入输出、已知限制和复现步骤。

“来源已核验”不代表本仓库已安装或完成运行测试；各页面会明确区分 Verified source 与 Tested。

## 5. 免责声明 | Disclaimer

本项目是社区知识整理与工作流研究项目，不代表任何模型、软件或服务的官方立场。上游代码、模型权重、数据集、素材和商标归各自权利人所有。使用前请阅读对应上游许可和服务条款。
