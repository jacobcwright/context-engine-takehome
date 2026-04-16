# MadeThis — Founding Engineer Take-Home

## The Context Engine

Build a system that analyzes a GitHub repository and generates structured context for AI coding agents. Benchmark it against DeepWiki. Deploy it. Beat it.

---

### Process

**Step 1: Start the clock**

If you haven't already, fill out the [Start Form](https://forms.gle/LdKDQpXqehbtvJHMA). Your 6-hour window begins when you submit that form.

**Step 2: Build, eval, deploy, iterate**

1. Build the context engine (Part 1)
2. Build the eval framework and benchmark against DeepWiki (Part 2)
3. Iterate on Parts 1 & 2 until you're getting **comparable or better results** than DeepWiki
4. Deploy to a live URL (Part 3)
5. Use remaining time to push quality, polish the product, and extend your eval

**Step 3: Submit**

Fill out the [Submission Form](https://forms.gle/E5v6maZA4Ef3SBFm6) with your repo, live URL, and video link.

---

### Part 1: The Context Engine

Build a tool that accepts a GitHub repository URL and produces structured context about the codebase. At minimum:

- **Project summary** — what it is, what stack, how it's organized
- **Architecture map** — key modules, how they relate, data flow
- **Conventions** — patterns, naming, error handling inferred from the code
- **Key files** — the most important files for a new contributor (human or AI) and why

Language, framework, and approach are your choice. CLI, web app, API — whatever you'd actually use.

### Part 2: The Eval Framework

Build a lightweight eval that compares your output against [DeepWiki](https://deepwiki.org/) for the same repos. DeepWiki is Cognition's (Devin AI) open documentation generator — read their [announcement post](https://cognition.ai/blog/deepwiki) for context on what it does and how it works.

See [`reference/deepwiki-mcp.md`](reference/deepwiki-mcp.md) for the DeepWiki MCP API details and examples.

See [`reference/eval-repos.md`](reference/eval-repos.md) for suggested repositories to evaluate against.

Your eval should:
- Run against at least 3 public repos of varying size/language
- Define clear evaluation dimensions (you decide what matters)
- Produce scored comparisons with explanations
- Be reproducible

### Part 3: Deploy It

Deploy your context engine to a live URL. Someone should be able to visit your site, enter a GitHub repo URL, and get results.

### Part 4: Writeup & Video

**Writeup (~1 page):**
- Architecture and key decisions
- Tradeoffs you made and why
- Eval results — where you beat DeepWiki, where you don't, and why
- What you'd build next with another week
- How you used AI tools (workflow, not just tool names)

**Video (5-10 min):**
- Demo your deployed product on a repo
- Walk through the codebase — structure, key decisions
- Walk through your eval — dimensions, results, what you'd improve

Screen recording with narration is fine. We want to hear you think about your own work.

---

### Rules

- **6 hours maximum.** Start form to submission form. If you're not done, submit what you have — we'd rather see how you prioritize under a constraint than a perfect result with unlimited time.
- **AI tools are encouraged.** Claude Code, Cursor, Copilot, agents — use whatever your normal workflow is. We care about the result and your ability to direct the process, not whether every line was hand-typed.
- **Language/framework is your choice.** Use what makes you productive.
- **Ship early, iterate.** Get something working and deployed before polishing. The progression from "working" to "comparable to DeepWiki" to "better than DeepWiki" is what we want to see.

### What We're Evaluating

| What | Why |
|---|---|
| **AI workflow** | How you leverage AI tools to build — methodology, not just usage |
| **Architecture & judgment** | Right-sized abstractions, good tradeoffs for the time |
| **Eval thinking** | Can you define "good", measure it, and reason about results? |
| **Product instinct** | Is the output useful or just technically impressive? |
| **Shipping** | Is it deployed? Does it work? Can we use it now? |
| **Communication** | The writeup and video reveal understanding code can't |

### Deliverables

1. GitHub repository (public or private — invite `jacobcwright` if private)
2. Live deployed URL
3. README with setup instructions
4. Eval results for 3+ repos
5. Written walkthrough (~1 page)
6. Video walkthrough (5-10 min, link in README)

### Questions?

Email jacob@madethis.com.
