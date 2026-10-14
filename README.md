# ADZ

Building automated systems and AI agents. Each folder below is one part of the system; tools are published as they are separated out.

## Wizz-agents - the flagship
The org for our autonomy framework. **[ultimate-nanobot](https://github.com/Wizz-agents/ultimate-nanobot)**: guarded single-purpose autonomous workers that only report success when they produced something, file their own failures, need a framework-graded canary to go live, and wait for a human on anything that spends. Built on and updated as the fleet grows.

## Claude
Tools built with and for Claude Code: the loop that runs the system. [All in this folder](https://github.com/wilshawdirect?tab=repositories&q=topic%3Aadz-claude)

| Repo | What it does |
|---|---|
| [claude-ops-queue](https://github.com/wilshawdirect/claude-ops-queue) | A task queue and skills for running Claude Code agents on a recurring schedule: dedup roots, a daily filing budget, section audits, machine-signal closes. |
| [llm-cascade](https://github.com/wilshawdirect/llm-cascade) | Local-first LLM routing with quality gates, fall-through and a JSONL usage ledger. Stdlib only. |

## Amun - Amazon
Sourcing and supplier tools for the Amazon lane. [All in this folder](https://github.com/wilshawdirect?tab=repositories&q=topic%3Aadz-amun)

| Repo | What it does |
|---|---|
| [wholesale-outreach-kit](https://github.com/wilshawdirect/wholesale-outreach-kit) | B2B outreach with a four-gate pre-send safety stack: MX validation, fact-check linting, reputation caps, suppression memory. |

## Raphael - affiliate marketing
The affiliate lane. [All in this folder](https://github.com/wilshawdirect?tab=repositories&q=topic%3Aadz-raphael)

| Repo | What it does |
|---|---|
| [uk-wholesale-reality](https://github.com/wilshawdirect/uk-wholesale-reality) | First-hand figures from a UK wholesale buyer's own records. **Live site: [wilshawdirect.github.io/uk-wholesale-reality](https://wilshawdirect.github.io/uk-wholesale-reality/)** |

## Blocko - manga and webtoon
The webtoon production tools live in the **[Wizz-agents](https://github.com/Wizz-agents)** organisation (script tools first; the series itself stays private).

## Horus - trading
Coming soon.

## General
Building blocks used across every part of the system. [All in this folder](https://github.com/wilshawdirect?tab=repositories&q=topic%3Aadz-general)

| Repo | What it does |
|---|---|
| [daemon-sentry](https://github.com/wilshawdirect/daemon-sentry) | Fleet liveness monitoring that judges each daemon by its own cadence and catches "green-but-dead" status lies. |
| [telegram-ops-kit](https://github.com/wilshawdirect/telegram-ops-kit) | A safe pattern for operations/approval Telegram bots: operator guard, verified approval cards, rate-limited sends. |
| [youtube-to-training-data](https://github.com/wilshawdirect/youtube-to-training-data) | YouTube video to a structured knowledge report plus instruction/response JSONL. Heuristic by default, LLM-pluggable. |
| [github-ingest](https://github.com/wilshawdirect/github-ingest) | Any public GitHub repo to one LLM-ready markdown digest, with a token budget that never truncates silently. |
