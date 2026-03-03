# ChatGPT - AI Digital Marketing Team

JSON configuration files for ChatGPT Custom GPTs.

## Files

```
chatgpt/
  ai-marketing-team.json           -- Full team (all 5 experts)
  standalone/
    research-specialist.json        -- Research Specialist
    content-lead.json               -- Content Lead
    visual-creative.json            -- Visual Creative
    data-analyst.json               -- Data Analyst
    account-manager.json            -- Account Manager
```

## Setup for Custom GPTs

1. Go to chatgpt.com.
2. Click "Explore GPTs" in the sidebar.
3. Click "Create" to build a new GPT.
4. In the "Configure" tab:
   - **Name**: Copy the `name` field from the JSON file.
   - **Description**: Copy the `description` field.
   - **Instructions**: Copy the `instructions` field.
   - **Conversation starters**: Copy the entries from `conversation_starters`.
5. Save and publish:
   - "Only me" for personal use.
   - "Anyone with a link" for sharing with your team.
   - "Public" to list in the GPT store.

## Quick Method (Paste Instructions Only)

If you prefer not to use the JSON structure:

1. Open the JSON file.
2. Copy the value of the `instructions` field (everything between the quotes).
3. Paste it directly into the GPT's Instructions field.
4. Manually set the name, description, and conversation starters.

## Sharing

- Use the GPT sharing link from the publish step.
- Or send the JSON file for others to create their own copy.

## Trigger Commands

ChatGPT uses `/` prefix for commands:
- `/help` - Show help guide
- `/start` - Brand onboarding (full team only)
- `/research` - Research Specialist
- `/content` - Content Lead
- `/visual` - Visual Creative
- `/data` - Data Analyst
- `/manager` - Account Manager
