# Claude - AI Digital Marketing Team

XML-formatted system prompts optimized for Claude.ai Projects.

## Files

```
claude/
  ai-marketing-team.xml            -- Full team (all 5 experts)
  standalone/
    research-specialist.xml         -- Research Specialist
    content-lead.xml                -- Content Lead
    visual-creative.xml             -- Visual Creative
    data-analyst.xml                -- Data Analyst
    account-manager.xml             -- Account Manager
```

## Why XML for Claude

Claude performs best with structured XML prompts. The XML tags help Claude parse instructions more precisely, leading to better adherence to rules, cleaner deliverables, and more reliable command handling.

## Setup for Claude.ai Projects

1. Go to claude.ai.
2. Create a new Project or open an existing one.
3. Click the Project settings (gear icon).
4. Under "Custom Instructions," paste the entire contents of the XML file.
5. Save the project.
6. Start a new conversation in that project and type `/help`.

## Setup for Claude API

Use the XML content as the `system` parameter in your API call:

```python
import anthropic

client = anthropic.Anthropic()

with open("claude/ai-marketing-team.xml", "r") as f:
    system_prompt = f.read()

message = client.messages.create(
    model="claude-sonnet-4-20250514",
    max_tokens=4096,
    system=system_prompt,
    messages=[{"role": "user", "content": "/help"}]
)
```

## Sharing

- Share the Claude Project directly with collaborators (they get the instructions automatically).
- Or send the XML file for others to paste into their own projects.

## Trigger Commands

Claude uses `/` prefix for commands:
- `/help` - Show help guide
- `/start` - Brand onboarding
- `/research` - Research Specialist
- `/content` - Content Lead
- `/visual` - Visual Creative
- `/data` - Data Analyst
- `/manager` - Account Manager
- `/status` - Progress tracker
- `/brief` - Campaign brief
