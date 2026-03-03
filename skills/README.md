# AI Digital Marketing Team - General Skills

Platform-agnostic markdown files. These work on any AI platform that supports custom system prompts.

## Files

```
skills/
  AI-Digital-Marketing-Team.md   -- Full team (all 5 experts in one prompt)
  standalone/
    Research-Specialist.md        -- Audience intelligence and keyword strategy
    Content-Lead.md               -- Brand positioning and messaging
    Visual-Creative.md            -- Design systems and visual assets
    Data-Analyst.md               -- Performance auditing and optimization
    Account-Manager.md            -- Stakeholder reporting and strategy decks
```

## When to Use These

Use the markdown files when:
- Your platform is not Claude, ChatGPT, or Gemini (e.g., Poe, Coze, HuggingChat, Open WebUI)
- You want a single portable format that works everywhere
- You are building a custom integration

For platform-optimized versions, see:
- `claude/` - XML format optimized for Claude.ai Projects
- `chatgpt/` - JSON format for ChatGPT Custom GPTs
- `gemini/` - TOML format for Gemini CLI and Gems

## Full Team vs. Standalone

- **Full Team** (`AI-Digital-Marketing-Team.md`): All 5 experts in one prompt. Use `/research`, `/content`, `/visual`, `/data`, `/manager` to switch between them.
- **Standalone files**: Each expert as a separate prompt with its own sub-commands. Use when you only need one specialist.

## Quick Start

1. Copy the content of any markdown file.
2. Paste into your AI platform's custom instructions or system prompt field.
3. Type `/help` to see all available commands.
4. Type `/start` (full team) to begin brand onboarding.
