# AI Digital Marketing Team

A professional AI-powered marketing team with 6 specialized experts. Packaged for Claude.ai, ChatGPT, Gemini, and any AI platform.

## Experts

| Expert | Focus | Trigger |
|--------|-------|---------|
| Research Specialist | Audience intelligence, ICP, keyword strategy | `/research` or `@research` |
| Content Lead | Brand positioning, messaging, content SOPs | `/content` or `@content` |
| Visual Creative | Brand identity, social templates, ad concepts | `/visual` or `@visual` |
| Data Analyst | Performance auditing, ROAS, A/B testing | `/data` or `@data` |
| SEO Specialist | Website audits, keyword rankings, blog content, link building | `/seo` or `@seo` |
| Account Manager | Stakeholder reporting, strategy decks | `/manager` or `@manager` |

## Project Structure

```
ai-marketing-team/
  README.md                         <-- You are here

  claude/                           <-- Claude.ai (XML format)
    ai-marketing-team.xml           -- Full team
    standalone/                     -- Individual experts
    README.md                       -- Setup instructions

  chatgpt/                          <-- ChatGPT (JSON format)
    ai-marketing-team.json          -- Full team
    standalone/                     -- Individual experts
    README.md                       -- Setup instructions

  gemini/                           <-- Gemini (TOML format)
    ai-marketing-team.toml          -- Full team
    standalone/                     -- Individual experts
    README.md                       -- Setup instructions

  skills/                           <-- General (Markdown format)
    AI-Digital-Marketing-Team.md    -- Full team
    standalone/                     -- Individual experts
    README.md                       -- Setup instructions
```

## Quick Start

1. Pick your platform folder (`claude/`, `chatgpt/`, or `gemini/`).
2. Read the README.md inside that folder for setup instructions.
3. Use the full team file for all 5 experts, or pick a standalone file for one specialist.
4. Type `/help` (or `@help` for Gemini) to see all commands.

## Recommended Workflow

```
/start     -->  /research  -->  /content  -->  /visual  -->  /data  -->  /seo      -->  /manager
 Brand          Audience        Brand          Design        Performance   Organic        Stakeholder
 Setup          Intel           Voice          System        Audit         Search         Reports
```

## What Each Expert Asks For

Every expert will ask you targeted questions before generating output. Here is what to prepare:

| Expert | What to Provide |
|--------|----------------|
| Research | Product name, top 3 competitors, customer pain points |
| Content | Brand guidelines, tone preferences, product features, channels |
| Visual | Brand colors (hex codes), logo, target platforms, style preferences |
| Data | Ad spend by channel, CPC, conversion rates, target ROAS |
| SEO | Website URL, competitors, target keywords, audience, brand voice |
| Manager | Stakeholder audience, report format, key metrics, reporting period |

## Platform Formats

| Platform | Format | Trigger Prefix | File Extension |
|----------|--------|---------------|----------------|
| Claude.ai | XML with structured tags | `/` | `.xml` |
| ChatGPT | JSON with GPT config fields | `/` | `.json` |
| Gemini | TOML with prompt field | `@` | `.toml` |
| General | Markdown | `/` | `.md` |

## Framework

All skills are built on the HubSpot Loop Marketing framework:
- **Express** - Define your brand identity
- **Tailor** - Customize messaging for your audience
- **Amplify** - Scale across channels with consistent assets
- **Evolve** - Optimize based on performance data
