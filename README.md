# Jonathan Haber

I build systems that keep AI agents aligned with what people actually mean — and run them in production.

Founder, [Next AI Labs](https://github.com/Next-AI-Labs-Inc) · Palo Alto, CA · [Portfolio](https://jonathan-haber-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/jryanhaber) · founder@ixcoach.com

---

## Alignment Harness for Claude Code — [alignment-harness.vercel.app](https://alignment-harness.vercel.app/)

Misalignment between a person and an agent rarely fails where it starts. It compounds: a misread message becomes a wrong plan, then code and passing tests aimed at the wrong target, then a session summary the next session trusts. The harness intervenes at each recurring moment ("fulcrum") in a Claude Code session where that drift gets in — so a misreading costs one sentence to fix instead of a day.

- In daily production use since March 2026: **39 hooks, 441 skills, a written operating protocol**, and searchable memory of past sessions and decisions
- **274,743 telemetry events** (since June 10) and **1,872 Claude Code sessions** (since July 16) run under it, as of Sept 28, 2026 — each figure reproducible from a documented command
- In my own use, roughly **5–10× more work completed** before a session drifts (author's estimate, not a controlled study)
- Being extracted into an installable, MIT-licensed plugin (193 skills packaged so far). Repo goes public after fresh-machine install testing.

## IX Coach — where it was proven

[IX Coach](https://ixcoach.com) is an AI coaching platform, live since 2023, with paying subscribers. It's the production system the harness grew out of.

- **14,104** real coaching conversations · **5,402** registered accounts (since May 2023)
- **24,060** commits since Jan 2023 · **~1.27M** lines of application code · **~243k** lines of tests
- Coaching quality measured from member behavior rather than model self-assessment; eleven monitors on key business metrics; staged releases

→ **[What has been built, with evidence](https://jonathan-haber-portfolio.vercel.app/the-work)**: every part, what it does, and how each number was measured.

## Open source

- [agent-swarm](https://github.com/Next-AI-Labs-Inc/agent-swarm): multi-agent Claude Code orchestration
- [ix-systems-docs](https://github.com/Next-AI-Labs-Inc/ix-systems-docs): representative slice of IX Coach backend architecture docs
- [Agentic-Sync](https://github.com/Next-AI-Labs-Inc/Agentic-Sync): agentic task management (Next.js / Tauri)
- [Video: my agentic / swarm coding workflow](https://www.loom.com/share/dc8bbdee917a4230b54435663367e034)

## Why

For twenty years my work has been about coherence: closing the gap between what people intend and what they actually do. Background in integral theory, applied coaching methodology and Zen practice. I now point that at the gap between what people mean and what AI does.
