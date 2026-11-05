<div align="center">

# Hi, I'm **Erkin Qarayev**

### Software Engineer: Python · TypeScript · React · LLM agents

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=white)](https://erkinres.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/garayev)
[![Email](https://img.shields.io/badge/Email-8B5CF6?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:erkinqara@proton.me)

</div>

---

## About

Software engineer with almost five years of experience, the last year mostly on LLM agent systems. Until June 2026 I worked on a JupyterLab-based analytics platform, from a React/TypeScript frontend extension to a Python/Tornado backend, and led its AI features. I also contribute upstream to JupyterLab and the Jupyter-AI ecosystem.

Available now. Open to remote work worldwide, as a contractor (B2B) or via an Employer of Record.

---

## What I'm working on now

- **[kishai](https://github.com/erkin98/kishai)**: a merge gate for LLM behaviour. YAML golden sets, deterministic checks first, a model judge only where nothing else can express the requirement, and a safety suite the judge is not allowed to decide. CI replays recorded outputs, so the gate needs no GPU and no network, and fails when a pass rate drops below the baseline.
- **[minitui](https://github.com/erkin98/minitui)**: a terminal agent where the model never writes code. It emits a spec from a frozen list of components, and a host process checks every shell command first (tree-sitter parser, deny-first rules, a hard floor for network fetches, secret reads and recursive deletes). In progress: nine packages and about 1,900 tests, no runnable CLI yet.
- **Open-source pull requests** in the Jupyter-AI stack (message edit and delete hooks, a fix for litellm global state leaking between providers, chat export), still in review.

---

## What I built

- **Datanout**: a notebook-native AI assistant on JupyterLab + Jupyter AI. A LangChain/LangGraph tool-calling agent with human-in-the-loop approval (per-tool allow, deny, ask), a full Model Context Protocol (MCP) client, cross-session memory, and an AST-based safety gate on model-written code.
- **Platform work**: primary author of the JupyterLab extension (custom file browser, a React/TypeScript widget library over Ant Design and AG Grid, the core plugin entry point) over a Python/Tornado backend; a data-pipeline wizard with a React Flow editor, later started again as a standalone FastAPI/Next.js app; a SQLAlchemy to SQLModel data-layer migration; a TypeScript-to-Python codegen tool that fails the build on frontend/backend drift; and instruction files and hooks for the team's AI coding assistants.
- **PanelBoom**: an internal design-to-code tool. Two Python FastMCP servers turn Figma mockups into Panel dashboards.
- **Internal dev tools**: a JupyterLab diagnostics and issue-reporter extension that files privacy-redacted Jira tickets, and a Python Redmine toolkit with a Typer CLI, a Textual TUI and an MCP server (506 tests).

---

## Open source (merged)

- **JupyterLab core** (15k+ stars): file-browser select-all fix, shipped in 4.2.0 ([#16026](https://github.com/jupyterlab/jupyterlab/pull/16026))
- **Jupyter-AI agent stack**: hardened the agent-driven terminal manager against environment-variable injection, with tests ([acp-client #25](https://github.com/jupyter-ai-contrib/jupyter-ai-acp-client/pull/25)); file and notebook attachment forwarding with path-traversal protection ([#24](https://github.com/jupyter-ai-contrib/jupyter-ai-acp-client/pull/24)); error handling in the Jupyternaut agent loop ([#42](https://github.com/jupyter-ai-contrib/jupyter-ai-jupyternaut/pull/42)); a mimetype field for notebook attachments ([jupyter-chat #383](https://github.com/jupyterlab/jupyter-chat/pull/383))
- **jupyter-chat**: a pycrdt minimum-version bump that stops silent tuple-to-null data loss ([#385](https://github.com/jupyterlab/jupyter-chat/pull/385))

---

## Other projects

- **diffuseai**: Python image-generation CLI with a verified end-to-end encryption layer (Argon2id, per-file HKDF-SHA256, AES-256-GCM) over a self-hosted SDXL backend
- **dashboard**: Next.js 15 / React 19 business-intelligence dashboard with a typed integration layer and Jest + Playwright visual-regression tests
- **js2tl**: TypeScript CLI that infers a Telegram TL schema from a JSON sample

---

<div align="center">
<sub>Python · TypeScript · React · JupyterLab · LangGraph · MCP · FastAPI · Security</sub>
</div>
