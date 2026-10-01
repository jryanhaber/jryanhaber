# Jonathan Haber

I design and ship AI products on Claude, end to end, and I build the systems that keep coding agents aligned with what people actually mean.

founder@ixcoach.com · Palo Alto, CA · [LinkedIn](https://www.linkedin.com/in/jryanhaber)

## Start here

- **[Portfolio](https://jonathan-haber-portfolio.vercel.app/)**: the single source of truth for my latest work, with links to source code
- **[What has been built](https://jonathan-haber-portfolio.vercel.app/the-work)**: the product, its data, the agent operating system, and how each number was measured
- **[Why I do this](https://jonathan-haber-portfolio.vercel.app/mission/personal-why)**: twenty years pursuing coherence, now aimed at coherence in AI systems
- **[Next AI Labs](https://jonathan-haber-portfolio.vercel.app/mission/next-ai-labs-seed)**: the vision, which is that keeping AI aligned decides whether it amplifies the world's broken systems or helps heal them
- **[Writing](https://jonathan-haber-portfolio.vercel.app/alignment-blog)**: essays on agent alignment, AI and human development
- **[Alignment Harness](https://alignment-harness.vercel.app/)**: the system I run Claude Code inside every day

---

## What I can do, and where it's proven

| Capability | Evidence |
|---|---|
| **Take a product from zero to paying users on frontier models**: product, design, full stack and operations, as one person | [IX Coach](https://ixcoach.com), live since 2023, with 14,104 real coaching conversations and 5,402 registered accounts since May 2023 → [the product](https://jonathan-haber-portfolio.vercel.app/the-work/the-product) |
| **Find unit economics that pay for themselves** | For over a month at high spend, paid acquisition earned back every dollar within 30 days and added about 45% of that spend to MRR on top. I counted every dollar spent and every sale while it ran. |
| **Put Claude to work inside real workflows**, with a human where the stakes call for one | An outreach engine with a human approval step, eleven monitors on key business numbers, staged releases → [running the business](https://jonathan-haber-portfolio.vercel.app/the-work/running-the-business) |
| **Measure whether AI behavior is actually good**, not whether it claims to be | Coaching quality tracked from what members do rather than model self-assessment, plus checks that looked right and did nothing, found by measuring and fixed → [what measuring revealed](https://jonathan-haber-portfolio.vercel.app/the-work/what-measuring-revealed) |
| **Kill my own ideas when the data says no** | Turned off IX Coach's one-question-per-turn rule in production in March 2026, after peak coaching data went against it |
| **Make agent-built software trustworthy at scale** | The Alignment Harness below: 1,872 Claude Code sessions and 274,743 telemetry events run under it |
| **Explain it so other builders can use it** | A public [fulcrum map](https://alignment-harness.vercel.app/) of where agents drift and what catches it, 457 written operating procedures for agents, an installable plugin in testing, and [essays](https://jonathan-haber-portfolio.vercel.app/alignment-blog) on the patterns behind it |
| **Build AI for human development** | Three and a half years of AI coaching aimed at growth rather than engagement → [why this exists](https://jonathan-haber-portfolio.vercel.app/the-work/the-problem) |

## Alignment Harness for Claude Code: [alignment-harness.vercel.app](https://alignment-harness.vercel.app/)

Misalignment between a person and an agent rarely fails where it starts. It compounds. A misread message becomes a wrong plan, then code and passing tests aimed at the wrong target, then a session summary the next session trusts. The harness intervenes at each recurring moment in a Claude Code session where that drift gets in (each one is called a fulcrum), so a misreading costs one sentence to fix instead of a day.

- In daily production use since March 2026: **39 hooks, 441 skills, a written operating protocol**, and searchable memory of past sessions and decisions
- **274,743 telemetry events** (since June 10) and **1,872 Claude Code sessions** (since July 16) have run under it as of Sept 28, 2026, and each figure can be reproduced from a documented command
- In my own use, roughly **5–10× more work completed** before a session drifts (my estimate, not a controlled study)
- It is being extracted into an installable, MIT-licensed plugin, with 193 skills packaged so far. The repo goes public after fresh-machine install testing.

## IX Coach: where it was proven

IX Coach is an AI coaching platform with paying subscribers. The harness grew out of building it.

- **The peak:** for over a month at high spend, paid acquisition paid back within 30 days and added about 45% of that spend to MRR. I believe it would scale with capital, and I'm glad to walk through the data. I chose to bring this work to a frontier-model team rather than raise to scale it.
- **14,104** coaching conversations · **5,402** registered accounts (since May 2023) · **24,060** commits since Jan 2023
- **How it's built:** I design and direct the work, and Claude Code agents write most of the code under my review. That way of working is what the harness exists to make reliable.

Everything current lives in the [portfolio](https://jonathan-haber-portfolio.vercel.app/). Full numbers, including the all-time averages, are available on request.

## Earlier open-source work (evidence)

- [ix-systems-docs](https://github.com/Next-AI-Labs-Inc/ix-systems-docs): architecture docs behind IX Coach's backend (debugging, orchestration)
- [agent-swarm](https://github.com/Next-AI-Labs-Inc/agent-swarm): multi-agent Claude Code orchestration
- [Agentic-Sync](https://github.com/Next-AI-Labs-Inc/Agentic-Sync): agentic task management (Next.js / Tauri)
- [Video: my agentic / swarm coding workflow](https://www.loom.com/share/dc8bbdee917a4230b54435663367e034)

---

<sub>Earlier: the original [Next AI Labs site](https://nextailabs.framer.website/), built on Framer. The portfolio now covers this better.</sub>
