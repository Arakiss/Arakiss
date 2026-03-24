# Petru Arakiss

**AI Engineering Lead @Atlax360**

I've spent 20 years building software and the last decade focused on AI systems. These days I architect multi-agent platforms, RAG pipelines, and document intelligence systems that actually ship to production.

## What I'm Working On

At Atlax360 I lead AI engineering across multiple enterprise platforms:

**Bifrost** - Document intelligence and RAG infrastructure. Semantic chunking, OCR pipelines, and search services. Python, FastAPI, pdfplumber, Tesseract, PyTorch, Supabase with pgvector.

**Orvian** - Workflow engine for B2B collections. Deterministic orchestration with human-in-the-loop escalation. Multi-channel communications, intent parsing, promise tracking. Next.js, React, Tailwind, TanStack Table.

**Polaris** - Internal knowledge assistant for Support, CS, Sales, and Dev teams. Conversational search with citations, role-based access, streaming UX. Built on top of Bifrost for retrieval. Next.js, Vercel AI SDK, Drizzle ORM.

These systems combine LLMs with production-grade architectures to solve real business problems. Same stack across all platforms because consistency matters.

## Stack

**Backend:** FastAPI, Python, Supabase, PostgreSQL, Redis

**Frontend:** Next.js, React, TypeScript, Tailwind CSS, shadcn/ui

**AI/ML:** OpenAI, Anthropic Claude, PyTorch, Transformers

**Databases:** PostgreSQL with pgvector for semantic search

**Tools:** Vercel AI SDK, Drizzle ORM, pydantic, structlog

## Approach

I spend a lot of time on context engineering. Not the trendy prompt engineering stuff, but actual architecture for how systems maintain and use context. Most RAG implementations fail because they treat context as an afterthought. I design systems where context flows naturally between agents, persists across interactions, and degrades gracefully when it gets stale.

Multi-agent systems work when each agent owns a clear domain and communicates through structured messages. The coordinator doesn't need to know everything, it just needs to know which agent to ask. Context engineering is about making sure the right information lands in the right place at the right time without bloating every prompt with the entire knowledge base.

## Open Source

I build tools when I see a gap worth filling:

**ghostty-warp** - Brings Warp-inspired features to Ghostty terminal. Auto-suggestions, syntax highlighting, fuzzy search, and themes.

**vestig** - Runtime-agnostic structured logging library with automatic PII sanitization and context propagation. Successor to nexlog.

**gitmuse** - AI-powered tool that analyzes staged changes and suggests meaningful commit messages.

**bunkit** - Modern CLI for Bun-powered projects. Scaffolds production-ready apps in seconds.

**commitloom** - AI-powered commit message generation. Makes git history actually useful.

## Philosophy

Most AI projects fail for boring reasons. People chase the latest model instead of solving the actual problem. They build impressive demos that fall apart under load. They forget about error handling, monitoring, rate limits, and all the unglamorous stuff that makes systems reliable.

RAG is just information retrieval with extra steps. Multi-agent systems are task decomposition, not sentience. The value is in the problem you solve, not the technique you use. I prefer maintainable systems that work over architectures that sound impressive in meetings.

The hard part isn't getting a prototype to work. It's making it reliable enough that you can sleep at night.

## Background

I work 100% remote from Madrid. Before Atlax360 I built everything from game engines to financial systems. I believe the best code is the code you don't have to write, which is why I'm interested in AI that reduces complexity instead of adding layers.

If you're working on something in the AI/document intelligence/automation space, reach out.

**Contact:** [petruarakiss@gmail.com](mailto:petruarakiss@gmail.com) | [LinkedIn](https://www.linkedin.com/in/petruarakiss/) | [petruarakiss.com](https://petruarakiss.com)
