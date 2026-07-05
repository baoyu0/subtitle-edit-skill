> **⚠️ 此仓库已归档** — 本 skill 已迁移至 [baoyu0/skills](https://github.com/baoyu0/skills/tree/main/media/subtitle-edit) 单体仓库。

---

# Subtitle Edit Agent Skill

Subtitle Edit CLI 操作 skill — 格式批量转换、时间偏移、编码处理、帧率修正。

支持 Hermes / Claude Code / Codex / OpenCode 等多 agent 环境。

## 功能

- 格式转换：SRT、ASS、SSA、VTT、MicroDVD 等互转
- 时间偏移：整体偏移或特定行范围偏移
- 帧率修正：23.976 ↔ 25 ↔ 29.97 等常见帧率转换
- 编码处理：UTF-8、GBK、BIG5 等编码批量转换
- 修复常见告警：重叠行、过长行、无效字符

## 使用

### Hermes Agent

```bash
skill_view(name='subtitle-edit')
```

其他 agent 读取 `SKILL.md` 后按指令执行。
