# Internal-tool lenses

Internal tools win when they delete toil a specific role already
hates. They lose when they become "a portal."

Pick **one lens per idea**.

## 1. Toil deletion

Find a weekly ritual that is copy-paste, status-chasing, or
ticket archaeology. The tool does the ritual and leaves an audit
trail. Humans only handle exceptions.

Good seeds: access requests, env promotion, "is this safe to
ship?", Friday cost report, on-call handoff.

## 2. Agent operations

Not another generic trace UI. A control surface for agents that
are already running: cost, blast radius, memory, tool allowlists,
eval failures, "what did it do to prod?"

Good seeds: spend guardrails, session replay for tool calls,
promotion from playground → prod, prompt/skill registry.

## 3. Context routing

The problem is not "search docs." It is getting the *right* shard
of context to the *right* actor (human or agent) at the moment of
action, with provenance.

Good seeds: incident war-room packets, PR risk briefings,
customer-account dossiers, "what changed since last on-call."

## 4. Platform self-service

Replace a platform-eng Slack DM with a narrow, opinionated
workflow that encodes the golden path. The UI is a wizard with
guardrails, not a dashboard of 40 tiles.

Good seeds: new service, new agent, new MCP server, preview env,
secret request, "give me a prod-like sandbox."

## 5. Developer enablement CLI

A single command that scores, fixes, or bootstraps a whole setup.
Internal tools that live in the terminal get used; portals get
bookmarked and forgotten.

Good seeds: repo health, agent eval harness, cloud-cost surprise
detector, "is my laptop/agent/homelab drifted?"

## 6. GitOps for humans

Make the desired state reviewable. The tool writes a PR or a
desired-state file; it does not click around a console.

Good seeds: homelab → team patterns, agent config, feature flags,
access policy, scorecards.

## 7. Exception inbox

Instead of monitoring everything, queue only the weird stuff:
policy violations, eval regressions, cost spikes, flaky deploys,
agents that looped. One inbox, three actions (ack / fix / ignore).

## 8. Dogfood a consumer idea at work

Some of the best internal tools are consumer-shaped: a teaching
loop, a ritual, a multiplayer object. If the team would use it
without being told to, it is a good internal idea.

## How to twist a lens

Name the *role* (on-call, platform, founder-operator, agent
author) and the *surface they already live in* (GitHub, Slack,
CLI, Cursor, PagerDuty). Ship into that surface first. A new
destination URL is a last resort.
