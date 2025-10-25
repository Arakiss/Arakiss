# Petru Arakiss

**Head of AI Engineering & Frontend Platform @Atlax360**

I've spent 19 years building software and the last decade focused on AI systems. These days I architect multi-agent platforms, RAG pipelines, and document intelligence systems that actually ship to production. I also run the frontend platform at Atlax360 because building good AI is pointless if nobody can use it.

## What I'm Working On

At Atlax360 I'm leading three major platforms:

**Bifrost** is our document intelligence engine. It processes everything from messy PDFs to Office documents, extracting structured data using a mix of Docling, pdfplumber, OCR (EasyOCR + Tesseract), and custom extraction pipelines. The backend runs on FastAPI with async Python, Supabase handles our data layer (PostgreSQL + pgvector for semantic search), and Redis for caching. Frontend is Next.js, TypeScript, Tailwind, shadcn/ui, and the Vercel AI SDK.

The interesting part is the multi-agent orchestration layer. Instead of cramming everything into one prompt, we have specialized agents that handle specific tasks (financial doc analysis, structured extraction, knowledge graph construction) and coordinate through a message bus. Each agent owns its domain and they communicate results instead of trying to be omniscient.

**Orvian** is a multi-tenant B2B debt recovery platform. We're building intelligent workflow orchestration for payment recovery that doesn't destroy business relationships. Right now we have the foundation: SSO with Azure AD, invitation flows, a generic RBAC engine that lets each workspace define its own permissions, and enterprise lead capture. Next up is the orchestration engine with LLM-assisted risk assessment, multi-channel communications (email, SMS, WhatsApp), and automated negotiation support. Built on the same stack as Bifrost because consistency matters more than novelty.

**Polaris** is our third platform (details are still under wraps, but it's in the same domain of intelligent automation and document processing).

## Stack

**Backend:** FastAPI, Python (async everything), Supabase, PostgreSQL, pgvector, Redis, Drizzle ORM

**Frontend:** Next.js 15, React 19, TypeScript, Tailwind CSS, shadcn/ui, Vercel AI SDK

**AI/ML:** OpenAI, Anthropic Claude, Transformers, sentence-transformers, PyTorch, tiktoken

**Document Processing:** Docling, pdfplumber, pypdf, python-docx, python-pptx, openpyxl, EasyOCR, Tesseract

**Dev Tools:** uv for Python packaging, pydantic everywhere, structlog for logging, typer for CLIs

## Side Projects

I build developer tools when something annoys me enough:

**gitmuse** and **commitloom** are CLI tools that use AI to generate meaningful commit messages. Because reading "fix stuff" in git history is useless.

**nexlog** is a logging library for Next.js that works in server, browser, and edge environments without making you want to throw your laptop.

## Philosophy

Most AI projects fail for boring reasons. People chase the latest model instead of solving the actual problem. They build impressive demos that fall apart under load. They forget about error handling, monitoring, rate limits, and all the unglamorous stuff that makes systems reliable.

RAG is just information retrieval with extra steps. Multi-agent systems are task decomposition, not sentience. The value is in the problem you solve, not the technique you use. I prefer maintainable systems that work over architectures that sound impressive in meetings.

The hard part isn't getting a prototype to work. It's making it reliable enough that you can sleep at night without worrying about what breaks when nobody is watching.

## Background

I work 100% remote from Madrid. Before Atlax360 I built everything from game engines to financial systems. I still believe the best code is the code you don't have to write, which is why I'm interested in AI that actually reduces complexity instead of adding abstraction layers.

If you're working on something in the AI/document intelligence/automation space, reach out.

**Contact:** [petruarakiss@gmail.com](mailto:petruarakiss@gmail.com) | [LinkedIn](https://www.linkedin.com/in/petruarakiss/)
