# Petru Arakiss

**AI Product & Platform Engineer @ Atlax360**

I build production AI systems where the model is one component inside a larger product surface: retrieval infrastructure, agent runtimes, guardrails, evals, traces, cost controls, permissions, and operator-facing interfaces.

I have 20 years of software delivery experience across product, frontend, backend, and platform work. The current focus is making AI useful in real financial operations, where answers need evidence, workflows need state, and failure modes need to be visible.

## Current Work

At Atlax360 I lead AI engineering across three production systems. The names are internal; the engineering shape is the signal.

**BIFROST**

Document intelligence and retrieval infrastructure for real-world inputs: ingestion quality gates, semantic chunking, semantic and visual retrieval, pgvector/HNSW search, caching, source-quality summaries, analytics, and honest no-answer behavior.

`Python` · `FastAPI` · `PostgreSQL` · `pgvector` · `Docling` · `PyTorch` · `Transformers`

**ORVIAN**

AI workflow runtime for B2B operational workflows: protected multi-tenant APIs, context assembly, durable memory, deterministic/cached/full-LLM execution tiers, run events, idempotency, queue processing, scheduled maintenance, and human-review metadata.

`TypeScript` · `Hono` · `PostgreSQL` · `Drizzle` · `Supabase` · `queues` · `scheduled jobs`

**Polaris**

Internal AI assistant product integrating BIFROST retrieval with MONARCH guardrails, cached safety-to-retrieval handoff, citations, streaming UX, visual query support, query analytics, and suggestion revalidation.

`Next.js` · `Vercel AI SDK` · `BIFROST` · `MONARCH` · `Drizzle ORM` · `PostgreSQL`

## Engineering Focus

- **Retrieval infrastructure:** ingestion, chunking, metadata, semantic search, visual search, citations, source quality, and no-answer paths.
- **Agent runtimes:** state, context assembly, tool use, execution tiers, idempotency, queues, handoffs, and human review.
- **AI guardrails:** prompt-injection checks, context sanitization, confidence thresholds, escalation rules, and audit trails.
- **Product reliability:** latency, token/cost metadata, observability, eval loops, regression checks, and operator-facing UX.
- **Full-stack delivery:** product judgment across interfaces, APIs, databases, deployment, and operational constraints.

## Selected Public Work

**[ghostty-warp](https://github.com/Arakiss/ghostty-warp)**

Ghostty configuration system with themes, presets, fonts, tmux integration, and a config switcher.

**[vestig](https://github.com/Arakiss/vestig)**

Runtime-agnostic structured logging with context propagation, observability primitives, and automatic PII sanitization.

**[gommage](https://github.com/Arakiss/gommage)**

Policy-as-code permission harness for AI coding agents: deterministic rules instead of prompt-only safety.

**[directed-systems-guide](https://github.com/Arakiss/directed-systems-guide)**

Research-backed field guide on human-AI collaboration, directed systems, and the limits of autonomous agents.

**[forgewright](https://github.com/Arakiss/forgewright)**

AI-first release system for LLM-assisted development, focused on semantic value rather than arbitrary release triggers.

## How I Think About AI Systems

Most AI systems fail for ordinary engineering reasons: weak context boundaries, vague orchestration, no eval path, poor observability, and no clear ownership when the model is wrong.

I prefer systems where the behavior can be inspected. Retrieval should show its evidence. Agents should expose state and stopping conditions. Guardrails should be explicit. Cost and latency should be visible. Human review should be part of the design, not a late-stage patch.

The hard part is not getting a prototype to answer once. The hard part is making the system reliable enough that people can use it when the input is messy, the context is incomplete, and the model is unsure.

## Contact

[petruarakiss.com](https://petruarakiss.com) · [LinkedIn](https://www.linkedin.com/in/petruarakiss/) · [GitHub](https://github.com/Arakiss) · [contact@petruarakiss.com](mailto:contact@petruarakiss.com)
