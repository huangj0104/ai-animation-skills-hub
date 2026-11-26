# Catalog | 资源目录

本目录用于索引模型、工具、节点/插件和 Agent Skills。不同类型分开记录，避免概念混淆。

建议逐步建立：

- `agent-skills.md` — 仅收录存在真实 `SKILL.md` 的 Agent Skills
- `video-models.md` — 视频生成与理解模型
- `image-models.md` — 图像生成与编辑模型
- `comfyui-nodes.md` — ComfyUI 节点及扩展
- `animation-tools.md` — 2D/3D、角色动画和动态图形工具
- `audio-tools.md` — TTS、配音、音效、音乐和音频处理工具
- `editing-tools.md` — 剪辑、字幕、合成和媒体处理工具

## 条目模板

```yaml
name: Example Project
type: model # agent-skill | model | tool | node-plugin | workflow | reference
official_url: https://example.com
purpose: Brief description
license: needs-review
version: unknown
status: needs-review
last_verified: YYYY-MM-DD
notes: Verify upstream facts before recommending
```

以上仅为格式示例，不代表真实项目条目。收录时必须替换示例字段并核验来源。
