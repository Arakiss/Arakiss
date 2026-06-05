# Petru Arakiss

**AI Engineering Lead · Production AI systems that hold up after the demo**

I build the engineering *around* the model — retrieval, agent runtimes, guardrails, evals, traces, and the operator interfaces that decide whether an AI system survives production. Twenty years in software; in machine learning since 2015, well before the current wave; full-time on production AI these last few years, inside regulated finance.

Most AI systems don't fail on the model. They fail on weak context boundaries, vague orchestration, no eval path, and no clear owner when the model is wrong.

## Current work

I lead AI engineering across three production systems at Atlax360. The names are internal; the engineering shape is the signal.

**BIFROST** — document intelligence and retrieval for the documents finance actually runs on: ingestion quality gates, semantic and visual chunking, pgvector/HNSW search, caching, source-quality scoring, analytics, and honest no-answer behavior.

`Python` · `FastAPI` · `PostgreSQL` · `pgvector` · `Docling` · `PyTorch` · `Transformers`

**ORVIAN** — multi-tenant AI workflow runtime for B2B operations: protected APIs, context assembly, durable memory, deterministic/cached/full-LLM execution tiers, run events, idempotency, queue processing, and human-review metadata when automation should stop.

`TypeScript` · `Hono` · `PostgreSQL` · `Drizzle` · `Supabase` · `queues`

**Polaris** — internal AI assistant integrating BIFROST retrieval with MONARCH guardrails, cached safety-to-retrieval handoff, citations, streaming UX, query analytics, and suggestion revalidation.

`Next.js` · `Vercel AI SDK` · `BIFROST` · `MONARCH` · `Drizzle` · `PostgreSQL`

## Selected public work

The same practice, extracted into tools you can read:

**AI agent harness & infrastructure**

- **[gommage](https://github.com/Arakiss/gommage)** · `Rust` — deterministic policy engine for coding agents: maps tool calls to capabilities, evaluates YAML rules, and signs every decision in a verifiable audit log. Hard-stops that policy can't bypass; determinism enforced by CI (10× per OS/locale).
- **[nahuali](https://github.com/Arakiss/nahuali)** · `TypeScript` — self-inspecting memory for agents: semantic/episodic/procedural memory with a governance layer that scores knowledge, surfaces contradictions, and flags blind spots over an append-only ledger.
- **[traceframe](https://github.com/Arakiss/traceframe)** · `Rust` — local-first, verifiable traces of agent runs: what the agent called, what it was allowed, and what failed. Hook ingestion for Codex/OMX harnesses.
- **[portico](https://github.com/Arakiss/portico)** · `TypeScript` — CLI-first browser-workflow runtime for agents: a sandboxed JS kernel over a capability-gated Playwright backend, with structured artifact traces and an MCP adapter.
- **[greco](https://github.com/Arakiss/greco)** · `Rust` — a research harness asking whether a coding-agent harness can measurably improve itself, within operator-defined evals and strict budgets. Honest about what's proven and what isn't.

**Observability & platform**

- **[vestig](https://github.com/Arakiss/vestig)** · `TypeScript` — runtime-agnostic structured logging with automatic PII sanitization (GDPR/HIPAA/PCI-DSS) and native W3C tracing. Zero dependencies; runs on Node, Bun, Deno, Edge, and the browser.
- **[eldr](https://github.com/Arakiss/eldr)** · `Rust` — zero-dependency Apple Silicon hardware monitor and thermal watchdog with a reversible-intervention model and hand-written FFI. A study in shipping discipline.

The through-line: permission boundaries, inspectable traces, governed memory, eval gates, and human-review boundaries for production AI.

## How I think about AI systems

I prefer systems whose behavior can be inspected. Retrieval shows its evidence. Agents expose state and stopping conditions. Guardrails are explicit. Cost and latency are visible. Human review is part of the design, not a late patch.

The hard part isn't getting a prototype to answer once. It's making the system reliable when the input is malformed, the context is incomplete, and the model is unsure.

## Open to

Staff, Principal, Architect, and Forward Deployed AI roles where production AI is the core of the product. Madrid · remote-first across the EU.

[petruarakiss.com](https://petruarakiss.com) · [LinkedIn](https://www.linkedin.com/in/petruarakiss/) · [GitHub](https://github.com/Arakiss) · [contact@petruarakiss.com](mailto:contact@petruarakiss.com)
