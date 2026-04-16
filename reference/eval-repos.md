# Suggested Eval Repositories

Use at least 3 repos for your evaluation. These are suggestions — you can substitute your own choices. Picking good eval repos is itself a design decision.

## Recommended Set

A mix of sizes, languages, and complexity levels:

### Small (~focused, well-structured)
- **[hono](https://github.com/honojs/hono)** — Fast web framework for the edge. TypeScript. Clean architecture, middleware patterns.
- **[zod](https://github.com/colinhacks/zod)** — TypeScript-first schema validation. Single-package, well-documented.
- **[tinygrad](https://github.com/tinygrad/tinygrad)** — Minimalist deep learning framework. Python. Dense, algorithmic code.

### Medium (~multi-package, real-world complexity)
- **[cal.com](https://github.com/calcom/cal.com)** — Scheduling platform. TypeScript monorepo (Next.js + tRPC + Prisma). Many packages, real business logic.
- **[langchain](https://github.com/langchain-ai/langchain)** — LLM framework. Python. Large surface area, many integrations.
- **[deno](https://github.com/denoland/deno)** — JavaScript runtime. Rust + TypeScript. Systems-level code with high-level APIs.

### Large (~sprawling, hard to summarize)
- **[next.js](https://github.com/vercel/next.js)** — React framework. TypeScript monorepo. Massive codebase, many subsystems.
- **[linux](https://github.com/torvalds/linux)** — The Linux kernel. C. The ultimate stress test for any analysis tool.

## What Makes a Good Eval Repo?

Consider selecting repos that test different failure modes:
- **Monorepo vs. single-package** — does your engine handle workspace structure?
- **Multiple languages** — can it detect and analyze polyglot projects?
- **Sparse vs. rich documentation** — does it rely on existing docs or infer from code?
- **Framework-heavy vs. standalone** — can it identify framework conventions?
