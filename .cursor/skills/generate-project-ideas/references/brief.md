# Full build brief

Write this only after the user picks an idea (or says "expand the
recommended one"). Keep it actionable. No strategy-consultant filler.

```markdown
# {Product Name}

## Pitch
One paragraph: who, job, twist.

## Who it is for
- Primary user:
- Scene they are in when they open it:
- What they do today instead:

## Why this, why now
Assumptions labeled as assumptions. Cite a source only if you have one.

## Demo moment
The 30-second thing you would record for a friend.

## MVP scope (yes)
3–7 bullets that will exist in v0.

## Explicitly out of scope
3–5 bullets people will try to sneak in.

## Information architecture
Key screens / commands / sessions. A short list, not a sitemap novel.

## Data and auth
What is stored, where, and the simplest auth that is still responsible.

## Suggested stack
Match the user's real tools. Call out the one new dependency that
creates the magic.

## Build order
1. Walking skeleton (deployed, ugly, real path)
2. The one magic interaction
3. Persistence / accounts if needed
4. Polish the demo moment
5. One distribution hook (CLI, template, public page, Slack command)

## Risks
- The way users shrug
- The technical unknown
- The ethical / safety line if agents or personal data are involved

## First week checklist
A Monday–Sunday list of concrete tasks, each finishable in a sitting.

## Definition of done for v0
A sentence they can evaluate honestly: "v0 is done when ___."
```

If they then say build it, stop using this skill and implement against
this brief.
