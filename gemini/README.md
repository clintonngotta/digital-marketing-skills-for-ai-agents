# Gemini - AI Digital Marketing Team

TOML-formatted skills for Gemini CLI and Gemini Gems.

## Files

```
gemini/
  ai-marketing-team.toml          -- Full team (all 5 experts)
  standalone/
    research.toml                  -- Research Specialist
    content.toml                   -- Content Lead
    visual.toml                    -- Visual Creative
    data.toml                      -- Data Analyst
    manager.toml                   -- Account Manager
```

## Setup for Gemini CLI

Place the TOML files in your Gemini CLI skills directory or reference them directly:

```bash
gemini --skill ai-marketing-team.toml
```

For standalone experts:
```bash
gemini --skill standalone/research.toml
gemini --skill standalone/content.toml
```

## Setup for Gemini Gems (Web)

1. Go to gemini.google.com and click "Gem manager" in the sidebar.
2. Click "New gem."
3. Set the name (e.g., "AI Marketing Team").
4. Copy the text between the triple quotes from the `prompt` field in the TOML file.
5. Paste into the "Instructions" field.
6. Save the Gem.

## Trigger Commands

Gemini uses `@` prefix for commands:
- `@help` - Show help guide
- `@start` - Brand onboarding
- `@research` - Research Specialist
- `@content` - Content Lead
- `@visual` - Visual Creative
- `@data` - Data Analyst
- `@manager` - Account Manager
