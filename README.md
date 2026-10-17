# Elijah Camp

Software engineer working full stack on a healthcare AI application. Before software I spent seven years as a Registered Behavior Technician. The work has the same shape in both fields: observe behavior, collect data, find the pattern, change the system. I apply that to production software and to Aurora, an ongoing study of what language models produce when they are given the opportunity to create.

## Work

Full-stack development on a healthcare AI application in care management (remote).

- **Frontend/app:** Next.js (App Router, server components), React, TypeScript, Tailwind, shadcn/Radix
- **Backend/cloud:** Node, Azure (Cosmos DB, Blob Storage, Entra ID, Container Apps, Azure OpenAI via Vercel AI SDK)
- **Infra/delivery:** Terraform, GitHub Actions, Azure DevOps
- **Practice:** test-driven development with Vitest; every PR records the original plan and the decisions made

Previously: production engineering and database administration. Sole DBA for a Koha library system serving 200+ users at 99.9% uptime over 18+ months, with custom MySQL triggers, stored procedures, and automated workflows.

## Research: Aurora

Aurora gives locally run language models a canvas, a small command vocabulary, and no reward signal, then records everything they do. The question is what a model produces when nothing tells it what to make, and how that changes when it can see the results of its own actions.

- 3,000+ logged sessions across open-weight models (Llama, Mistral, Qwen, Phi, DeepSeek, Gemma, Kimi-VL), run on consumer hardware via llama-cpp-python
- Every thought, action, and canvas state stored in MySQL, with each session's settings and code version recorded for reproducibility
- Current work: vision-language models that see the actual canvas before and after their own commands, tested one model at a time until the setup is stable
- Design principle carried over from behavior analysis: natural contingency (the model perceives the consequences of its actions) instead of reward shaping

## Personal projects

These repos are private. I'm happy to walk through any of them.

- **PHT** - a habit tracker with a TypeScript API and a vanilla TypeScript frontend built as a desktop-style UI with a snap-grid window manager. Versioned releases with one-command rollback, integration tests against a real MySQL instance, revocable sessions, single-VPS deploy.
- **LumpyLP** - an indexer for Creative Commons and public-domain music. 645,000+ tracks ingested from 11+ sources through per-source resolvers, a license-canonicalization quality gate, dead-link sweeps, and geocoded artist locations. Currently paused.
- **LLM Lab** - a local workbench for inference and LoRA fine-tuning on consumer hardware.

## How I work

AI-assisted development has been my primary workflow for about three years: a planning agent, a coding agent, and a separate review agent that has not seen the work. Changes are gated, and decisions are written down.

## Background

- B.A. Computer Science, University of Colorado Denver (2026)
- 7 years as an RBT: ABA, AAC systems for nonverbal clients, behavioral data collection and analysis
- 4 years building accessible systems, with WCAG applied in production work

## Stack

**Languages:** TypeScript, JavaScript, Python, SQL, Bash
**Data:** MySQL, PostgreSQL, MongoDB, SQLite, Cosmos DB
**Infrastructure:** Azure, Terraform, Docker, Kubernetes, Linux, nginx

## Contact

**LinkedIn:** [linkedin.com/in/elijah-camp-106708282](https://linkedin.com/in/elijah-camp-106708282)
