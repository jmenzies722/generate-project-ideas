# generate-project-ideas

A Cursor skill that invents **cool, buildable** project ideas — consumer
products or internal tools — and turns them into briefs you can start
tonight.

It does not dump a list of names. Each idea gets a problem, a demo
moment, an MVP, a stack guess, a risk, and scores.

## Install

### Use it in this repo

Open this repository in Cursor. The skill lives at
`.cursor/skills/generate-project-ideas/` and is picked up automatically.

### Use it in every project

Copy the skill folder into your user skills directory:

```bash
git clone https://github.com/jmenzies722/generate-project-ideas.git
cp -R generate-project-ideas/.cursor/skills/generate-project-ideas ~/.cursor/skills/
```

Then start a new Agent chat. Confirm it under **Cursor Settings → Skills**.

### Invoke it

- Type `/generate-project-ideas` in Agent chat
- Or say things like "what should I build," "give me internal tool ideas,"
  "weekend consumer app ideas"

## What to say

Keep it short. Constraints help, a questionnaire is not required.

```text
/generate-project-ideas
consumer, two weekends, Next.js, something I can dogfood in NYC
```

```text
/generate-project-ideas
internal tools for an agent platform team, CLI-first
```

```text
expand the recommended one
```

## What you get

1. Five ideas from **different lenses** (not five chatbots)
2. Scores: Cool / Pain / Ship / Distinct
3. One recommended build
4. Optional full brief once you pick

Stale defaults (todo apps, ChatGPT wrappers, Notion clones) are banned
on purpose.

## Layout

```text
.cursor/skills/generate-project-ideas/
├── SKILL.md
└── references/
    ├── banned.md
    ├── brief.md
    ├── consumer-lenses.md
    ├── internal-lenses.md
    └── scoring.md
```
