# Skills

Agent Skills and prompts. Each skill follows the open [Agent Skills](https://agentskills.io/specification) format: a folder in `skills/` with a `SKILL.md` and its references.

| Skill | What it does |
|---|---|
| [life-envision](skills/life-envision/SKILL.md) | A 30–45 minute guided conversation that pictures the life you want in specific detail, then delivers a four-chapter profile: your life, what you want most, what it takes (costs with workings, plus time, skills, people, place) and who you're becoming. [Example output](examples/life-envision-sample.md). |

## Install

**Claude (web, desktop, mobile):** download `life-envision.zip` from [Releases](../../releases), then Settings → Capabilities → Skills → Upload skill. Start a chat with "I'd like to work out what I want from life."

**Claude Code:**
```
/plugin marketplace add SamBrookfield/skills
/plugin install life-envision@sambrookfield-skills
```
or copy `skills/life-envision` into `~/.claude/skills/`.

**Other Agent Skills tools (Codex, Gemini CLI, Cursor, Copilot):** `npx skills add SamBrookfield/skills`, or copy the folder into the tool's skills directory.

**ChatGPT, Gemini app and any other chat:** attach [`prompts/life-envision.prompt.md`](prompts/life-envision.prompt.md) to a new chat and say "Follow this file exactly and start." For repeat use, add it to a Custom GPT or Gem.

## Before you start

- It asks about your home, family, work and pay; use an AI tool and account you're comfortable sharing that with.
- Money figures are estimates at today's prices, not financial advice.
- It's reflective coaching, not therapy. Say "pause" to get a resume block, or "let's wrap up" to finish early.
