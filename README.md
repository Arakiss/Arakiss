# Petru Arakiss

**Head of AI Engineering & Frontend Platform @ Atlax360**

I've spent 19 years building software and the last decade focused on AI systems. These days I architect multi-agent platforms, RAG pipelines, and document intelligence systems that actually ship to production. I also run the frontend platform at Atlax360 because building good AI is pointless if nobody can use it.

## What I'm Working On

At Atlax360 I lead AI engineering across multiple enterprise platforms:

**Bifrost** - Document intelligence and RAG infrastructure for organizational knowledge management. Multi-agent architecture that processes complex documents and enables semantic search at scale.

**Orvian** - Multi-tenant platform for intelligent business process automation and workflow orchestration.

**Polaris** - Conversational AI interface for internal knowledge access. Provides natural language interaction with organizational data across multiple languages.

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

**bunkit** - Modern CLI for Bun-powered projects. Scaffolds production-ready apps in seconds.

**ghostty-warp** - Brings Warp-inspired features to Ghostty terminal. Auto-suggestions, syntax highlighting, fuzzy search, and themes.

**commitloom** - AI-powered commit message generation. Makes git history actually useful.

**nexlog** - Logging library for Next.js that works across server, browser, and edge without fighting you.

## Philosophy

Most AI projects fail for boring reasons. People chase the latest model instead of solving the actual problem. They build impressive demos that fall apart under load. They forget about error handling, monitoring, rate limits, and all the unglamorous stuff that makes systems reliable.

RAG is just information retrieval with extra steps. Multi-agent systems are task decomposition, not sentience. The value is in the problem you solve, not the technique you use. I prefer maintainable systems that work over architectures that sound impressive in meetings.

The hard part isn't getting a prototype to work. It's making it reliable enough that you can sleep at night.

## Background

I work 100% remote from Madrid. Before Atlax360 I built everything from game engines to financial systems. I believe the best code is the code you don't have to write, which is why I'm interested in AI that reduces complexity instead of adding layers.

If you're working on something in the AI/document intelligence/automation space, reach out.

**Contact:** [petruarakiss@gmail.com](mailto:petruarakiss@gmail.com) | [LinkedIn](https://www.linkedin.com/in/petruarakiss/)
