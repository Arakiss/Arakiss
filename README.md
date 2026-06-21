# Petru Arakiss

**AI Engineering Lead. Production AI, retrieval, agent runtimes, evals, traces, and operator workflows.**

I work on the engineering around language models: retrieval systems, agent and workflow runtimes, guardrails, eval loops, traces, permissions, cost and latency controls, and the product screens that make failures visible.

Twenty years in software. Machine learning since 2015. Current work is inside regulated finance, so public detail has a boundary: I can name the systems and the engineering shape, but not expose private implementation details.

Most AI systems do not fail only on model quality. They fail on weak context boundaries, vague orchestration, missing evals, hidden cost, unclear permissions, and no owner when the model is wrong.

## Current private production context

I lead AI engineering across three systems at Atlax360. The implementations are private. The architecture class is public.

**BIFROST.** Document intelligence and retrieval for financial documents: ingestion quality gates, semantic and visual chunking, pgvector/HNSW search, caching, source-quality scoring, analytics, and explicit no-answer behavior when evidence is weak.

`Python` · `FastAPI` · `PostgreSQL` · `pgvector` · `Docling` · `PyTorch` · `Transformers`

**ORVIAN.** Multi-tenant AI workflow runtime for B2B operations: protected APIs, context assembly, durable memory, deterministic/cached/full-LLM execution tiers, run events, idempotency, queue processing, and human-review metadata when automation should stop.

`TypeScript` · `Hono` · `PostgreSQL` · `Drizzle` · `Supabase` · `queues`

**Polaris.** Internal AI assistant integrating BIFROST retrieval with MONARCH guardrails, cached safety-to-retrieval handoff, citations, streaming UX, query analytics, and suggestion revalidation.

`Next.js` · `Vercel AI SDK` · `BIFROST` · `MONARCH` · `Drizzle` · `PostgreSQL`

## Selected public work

These repos are not a complete production system. They are public pieces of the way I think about agentic engineering, observability, local tooling, and developer environments.

**Agent harness and governance**

- **[gommage](https://github.com/Arakiss/gommage)** (Rust): policy-as-code permission harness for AI coding agents. Deterministic allow, deny, and ask decisions with audit evidence.
- **[nahuali](https://github.com/Arakiss/nahuali)** (Rust): self-inspecting memory for AI agents. Evidence, provenance, health signals, and an optional Ed25519-signed tamper-evident ledger.
- **[traceframe](https://github.com/Arakiss/traceframe)** (Rust): local-first trace recorder for AI agent workflows. Append-only run evidence, hook ingestion, ledger indexing, reports, and CI gates.
- **[greco](https://github.com/Arakiss/greco)** (Rust): research harness for typed, layered, reversible coding-agent harness changes under operator-owned evals and budgets.

**Observability and local systems**

- **[vestig](https://github.com/Arakiss/vestig)** (TypeScript): runtime-agnostic structured logging with context propagation, observability primitives, and automatic PII sanitization.
- **[eldr](https://github.com/Arakiss/eldr)** (Rust): zero-dependency Apple Silicon hardware monitor and thermal watchdog: CPU/GPU/ANE power, per-core load, temperatures, fans, and battery without sudo.

**Developer environment**

- **[ghostty-warp](https://github.com/Arakiss/ghostty-warp)** (Shell): Ghostty terminal environment for Linux: themes, presets, fonts, tmux integration, and a config switcher for a Warp-like workflow.

## How I think about AI systems

I prefer systems whose behavior can be inspected. Retrieval should show its evidence. Agents should expose state and stopping conditions. Guardrails should be explicit. Cost and latency should be visible. Human review should be designed into the path, not patched on after a failure.

The useful public claim is simple: if a repo, source, trace, test, or product constraint supports a statement, link it. If the work is private, say where the public boundary is.

## Open to

Staff, Principal, Architect, and Forward Deployed AI roles where production AI is the core product work.

Madrid. Remote-first across the EU.

[petruarakiss.com](https://www.petruarakiss.com) · [LinkedIn](https://www.linkedin.com/in/petruarakiss/) · [GitHub](https://github.com/Arakiss) · [contact@petruarakiss.com](mailto:contact@petruarakiss.com)
