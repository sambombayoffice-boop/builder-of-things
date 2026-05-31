# Paperclip — study notes (governed agent orchestration)

Reference for Builder of Things / Bombaybot & Command OS positioning. Paperclip is
the open-source counterpoint to Polsia: same dream (AI runs the company), opposite
stance — self-hosted, governed, human-in-command.

## What it is

"The open-source app everyone uses to manage agents at work" — a control plane for
teams of AI agents. Node/TypeScript server + React UI you self-host (MIT). Exploding
fast (~68k GitHub stars). Start with `npx paperclipai onboard --yes` (Node 20+,
embedded Postgres). The model: **you're the boss** — every agent has *a boss, a
title, and a job description*.

Core features:
- **Governance & approvals** — review/approval stages, board sign-off, audit logs.
  "Nothing ships without your sign-off."
- **Budget/cost control** — per-agent monthly budgets, hard-stops; overspend
  auto-pauses agents and cancels queued work.
- **Bring-your-own-agent** — runtime-agnostic, no provider lock-in.
- **Heartbeats** (scheduled activation), **multi-company** isolation, **ticket
  system** with audit trail, **org-chart** hierarchies, mobile-ready UI.

## Why it matters to us

- **It's the deliberate antidote to every Polsia failure** — autonomy theater,
  abandonment, runaway spend, security scares. Paperclip answers each with control,
  approvals, budget caps, and audit logs. The market is rewarding it (68k stars fast
  vs Polsia's $30M-but-hated).
- **It validates the "Command" thesis.** People want governed, human-in-command
  agents — exactly what Command OS's name promises.
- **It sets the table stakes.** Approvals, budget hard-stops, audit logs, org chart,
  BYO-agent are now *expected*, not differentiators.

## Where we differentiate (don't out-dashboard them)

- **Claude-native depth** vs their runtime-agnostic breadth — lean into skills,
  hooks, memory, and the local voice/Vesper layer that only a Claude Code-native OS
  does well.
- **Personal/creative studio** angle — Bombaybot makes *things* (films, sites,
  products). They run generic "company ops"; we ship artifacts.
- **Local, on-your-machine, always-on** posture (the voice assistant) vs their
  server/dashboard. Own "it lives with you," not "another browser tab."

## One-line takeaway

Treat Paperclip's feature set as the **category baseline** to match on governance;
win on **Claude-native craft + the studio/personal, lives-with-you** angle rather
than competing as a generic agent dashboard.

Sources: github.com/paperclipai/paperclip · paperclip.ing ·
mindstudio.ai (Paperclip explainer) · eweek.com.
