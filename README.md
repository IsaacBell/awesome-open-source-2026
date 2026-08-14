# Awesome Open Source 2026

> Curated standout open-source projects from 2026 — AI tooling, data ingestion, self-hosted apps, and developer infrastructure.

## Contents

- [AI & LLM Tooling](#ai--llm-tooling)
  - [Frameworks & Structured Output](#frameworks--structured-output)
  - [Agents & Workflow Automation](#agents--workflow-automation)
  - [Inference & Model Serving](#inference--model-serving)
  - [Evals & Observability](#evals--observability)
- [Data Ingestion & Scraping](#data-ingestion--scraping)
- [Databases](#databases)
- [Self-Hosted & Infrastructure](#self-hosted--infrastructure)
  - [Personal & Media](#personal--media)
  - [Productivity & Collaboration](#productivity--collaboration)
  - [Cloud & Orchestration](#cloud--orchestration)
  - [Self-Hosted AI](#self-hosted-ai)
- [Developer Tools](#developer-tools)
- [Web Frameworks](#web-frameworks)
- [Related Awesome Lists](#related-awesome-lists)

## AI & LLM Tooling

### Frameworks & Structured Output

- [DSPy](https://github.com/stanfordnlp/dspy) - Framework for programming — not prompting — language models, from Stanford NLP.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Type-safe agent framework built on Pydantic validation.
- [Haystack](https://github.com/deepset-ai/haystack) - Production-ready framework for building LLM applications and RAG pipelines.
- [Outlines](https://github.com/dottxt-ai/outlines) - Structured output generation for LLMs, letting models follow schemas and regex.
- [Instructor](https://github.com/567-labs/instructor) - Structured outputs for LLMs via function-calling style interfaces in Python.

### Agents & Workflow Automation

- [OpenOutreach](https://github.com/eracle/OpenOutreach) - Agentic email automation: describe your product, define the target market, and let the AI find and contact leads.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Low-level orchestration framework for stateful, multi-agent LLM applications.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing AI agents.
- [Agno](https://github.com/agno-agi/agno) - Lightweight framework for building multi-modal AI agents.
- [Dify](https://github.com/langgenius/dify) - Open-source LLM app development platform with workflows and RAG.
- [Flowise](https://github.com/FlowiseAI/Flowise) - Drag-and-drop UI for building LLM applications and agents.
- [n8n](https://github.com/n8n-io/n8n) - Fair-code workflow automation platform with AI agent support.

### Inference & Model Serving

- [LiteLLM](https://github.com/BerriAI/litellm) - Fast AI gateway with a Rust core; calls 100+ LLM APIs in OpenAI format with cost tracking, guardrails, and load balancing.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput inference and serving engine for LLMs.
- [SGLang](https://github.com/sgl-project/sglang) - Fast serving framework for LLMs and multi-modal models.
- [Ollama](https://github.com/ollama/ollama) - Run open-source LLMs locally with a simple CLI and API.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - C/C++ inference for LLMs optimized for CPU and GPU.
- [LocalAI](https://github.com/mudler/LocalAI) - Self-hosted, OpenAI-compatible inference engine for local models.
- [Text Generation Inference](https://github.com/huggingface/text-generation-inference) - Hugging Face's production server for serving large language models.

### Evals & Observability

- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform: evals, observability, metrics, prompt management, and datasets. Integrates with OpenTelemetry, LangChain, and LiteLLM.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - Open-source tool for red-teaming and evaluating LLM applications.
- [Ragas](https://github.com/explodinggradients/ragas) - Open-source framework for evaluating RAG pipelines.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - Open-source AI observability and evaluation platform.
- [Weave](https://github.com/wandb/weave) - Weights & Biases toolkit for tracing and evaluating AI applications.
- [Opik](https://github.com/comet-ml/opik) - Open-source LLM evaluation and observability platform from Comet.
- [Helicone](https://github.com/Helicone/helicone) - Open-source LLM observability and cost-tracking proxy.

## Data Ingestion & Scraping

- [Marker](https://github.com/datalab-to/marker) - Converts PDFs to markdown and JSON quickly with high accuracy.
- [Chonkie](https://github.com/feyninc/chonkie) - Lightweight ingestion library for fast, efficient, robust RAG pipelines.
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - Open-source, LLM-friendly web crawler and scraper.
- [Firecrawl](https://github.com/firecrawl/firecrawl) - API for turning websites into LLM-ready markdown data.
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - Open-source library for parsing and cleaning unstructured documents.
- [Docling](https://github.com/docling-project/docling) - Document parsing toolkit that converts PDFs and office docs to structured formats.
- [Scrapy](https://github.com/scrapy/scrapy) - Fast, extensible web scraping framework for Python.
- [Trafilatura](https://github.com/adbar/trafilatura) - Command-line tool for extracting clean text from web pages.

## Databases

- [DuckDB](https://github.com/duckdb/duckdb) - In-process analytical SQL database for fast query workloads.
- [ClickHouse](https://github.com/ClickHouse/ClickHouse) - Columnar database for real-time analytics.
- [SurrealDB](https://github.com/surrealdb/surrealdb) - Multi-model database with SQL-like queries and real-time features.
- [Neon](https://github.com/neondatabase/neon) - Serverless Postgres with branching and autoscaling.
- [Supabase](https://github.com/supabase/supabase) - Open-source Firebase alternative with Postgres at its core.
- [PocketBase](https://github.com/pocketbase/pocketbase) - All-in-one backend with database, auth, and file storage in a single binary.
- [Qdrant](https://github.com/qdrant/qdrant) - High-performance vector search engine and database.
- [Milvus](https://github.com/milvus-io/milvus) - Scalable open-source vector database built for production.
- [pgvector](https://github.com/pgvector/pgvector) - Postgres extension for vector similarity search.
- [LanceDB](https://github.com/lancedb/lancedb) - Embedded vector database built for AI applications.

## Self-Hosted & Infrastructure

### Personal & Media

- [Immich](https://github.com/immich-app/immich) - High-performance self-hosted photo and video management.
- [Nextcloud](https://github.com/nextcloud/server) - Self-hosted productivity platform for files, calendars, and collaboration.
- [Home Assistant](https://github.com/home-assistant/core) - Open-source home automation platform focused on local control.
- [Jellyfin](https://github.com/jellyfin/jellyfin) - Free self-hosted media server for streaming your media.
- [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) - Self-hosted web-based PDF manipulation toolkit.
- [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) - Document management system that digitizes paper into searchable archives.
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - Lightweight password manager server compatible with Bitwarden clients.
- [Linkwarden](https://github.com/linkwarden/linkwarden) - Self-hosted bookmark manager for saving and organizing links.

### Productivity & Collaboration

- [NocoDB](https://github.com/nocodb/nocodb) - Free, self-hostable Airtable alternative.
- [Documenso](https://github.com/documenso/documenso) - The open-source DocuSign alternative for digital signing.
- [Penpot](https://github.com/penpot/penpot) - Open-source design platform for product teams needing scalable collaboration.
- [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) - Open-source Notion alternative for knowledge and project management.
- [AFFiNE](https://github.com/toeverything/AFFiNE) - Open-source workspace combining docs, whiteboards, and databases.
- [Outline](https://github.com/outline/outline) - Team knowledge base with a wiki-style editor.
- [Cal.com](https://github.com/calcom/cal.com) - Open-source scheduling infrastructure for appointment booking.

### Cloud & Orchestration

- [Coolify](https://github.com/coollabsio/coolify) - Self-hostable PaaS alternative to Vercel, Heroku, and Netlify with 280+ one-click services.
- [PostHog](https://github.com/PostHog/posthog) - Product analytics, session replay, feature flags, and experimentation.
- [Kestra](https://github.com/kestra-io/kestra) - Open-source orchestration platform for data pipelines and workflows.
- [Temporal](https://github.com/temporalio/temporal) - Durable execution platform for reliable distributed workflows.
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - Self-hosted monitoring tool for tracking service availability.
- [Portainer](https://github.com/portainer/portainer) - Lightweight management UI for Docker and Kubernetes.

### Self-Hosted AI

- [Open WebUI](https://github.com/open-webui/open-webui) - Self-hosted web interface for interacting with local LLMs.
- [LibreChat](https://github.com/danny-avila/LibreChat) - Open-source ChatGPT-style interface supporting multiple AI providers.
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) - All-in-one AI desktop app with RAG and multi-user support.
- [Lobe Chat](https://github.com/lobehub/lobe-chat) - Open-source ChatGPT-style chat framework with plugin support.
- [Jan](https://github.com/janhq/jan) - Offline-first desktop app for running AI models locally.

## Developer Tools

- [Semgrep](https://github.com/semgrep/semgrep) - Lightweight static analysis for many languages; finds bug variants with pattern-based rules.
- [Ast-grep](https://github.com/ast-grep/ast-grep) - CLI tool for code structural search, lint, and rewriting, written in Rust.
- [Reviewdog](https://github.com/reviewdog/reviewdog) - Automated code review tool that integrates with any code analysis tool.
- [Rulesync](https://github.com/dyoshikawa/rulesync) - Utility CLI for keeping AI coding agent rules in sync.
- [Slidev](https://github.com/slidevjs/slidev) - Presentation slides for developers, written in Markdown.
- [uv](https://github.com/astral-sh/uv) - Extremely fast Python package and project manager written in Rust.
- [Ruff](https://github.com/astral-sh/ruff) - Fast Python linter and formatter written in Rust.
- [Biome](https://github.com/biomejs/biome) - Fast JavaScript and TypeScript toolchain combining linting and formatting.
- [Zed](https://github.com/zed-industries/zed) - High-performance collaborative code editor from the creators of Atom.
- [Bun](https://github.com/oven-sh/bun) - JavaScript runtime, bundler, and package manager in one tool.
- [Deno](https://github.com/denoland/deno) - Secure JavaScript and TypeScript runtime by the creator of Node.js.
- [Renovate](https://github.com/renovatebot/renovate) - Automated dependency update tool for repositories.
- [lazygit](https://github.com/jesseduffield/lazygit) - Simple terminal UI for git commands.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - Smarter cd command with fuzzy directory jumping.

## Web Frameworks

- [Next.js](https://github.com/vercel/next.js) - React framework with server-side rendering and static generation.
- [Nuxt](https://github.com/nuxt/nuxt) - Vue framework for building full-stack web applications.
- [SvelteKit](https://github.com/sveltejs/kit) - Application framework for Svelte with SSR and routing.
- [Astro](https://github.com/withastro/astro) - Content-driven web framework that ships zero-JavaScript sites.
- [SolidJS](https://github.com/solidjs/solid) - Reactive JavaScript library for building user interfaces.
- [Qwik](https://github.com/QwikDev/qwik) - Resumable web framework for instant-loading applications.
- [Remix](https://github.com/remix-run/remix) - Full-stack React framework for the modern web.
- [Hono](https://github.com/honojs/hono) - Ultrafast web framework for edge runtimes in JavaScript and TypeScript.
- [FastAPI](https://github.com/fastapi/fastapi) - Modern Python web framework for building APIs with automatic docs.

## Related Awesome Lists

- [Awesome Self Hosted](https://github.com/awesome-selfhosted/awesome-selfhosted#readme)
- [Awesome LLM](https://github.com/himself65/awesome-llm#readme)
- [Awesome Open Source](https://github.com/kevinwang/awesome-open-source#readme)
- [Awesome AI](https://github.com/owainlewis/awesome-artificial-intelligence#readme)
- [Awesome Databases](https://github.com/numetriclabz/awesome-db#readme)

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under the CC0 1.0 Universal license.
