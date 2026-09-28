# Yuan Skills

Fate0x01 公开分享的 Agent 技能，采用 `SKILL.md` 格式，可用于 Claude Code、Codex 等支持技能的 Agent。

Agent skills in the `SKILL.md` format, shared by Fate0x01. Works with Claude Code, Codex and other agents that support skills.

## 技能

| 技能 | 作用 |
| --- | --- |
| [yuan-short-answer](skills/yuan-short-answer/) | 你要求"一句话""只要结论""别展开"时，把最终答复压到最短；排查、验证和交付物照常完整，只精简回复本身。Agent 会按你的措辞自动启用。 |

## 安装

用 [Skills CLI](https://github.com/vercel-labs/skills) 安装：

```bash
npx skills@latest add Fate0x01/yuan-skills
```

也可以手动把 `skills/<技能名>/` 整个目录复制到 Agent 的技能目录，例如 Claude Code 的 `~/.claude/skills/`，或 Codex 的 `~/.agents/skills/`。

## 许可证

[MIT](LICENSE)
