<div align="center">

# Hi, I'm **Erkin Qarayev**

### Senior Software Engineer — Python · TypeScript · React

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=white)](https://erkinres.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/garayev)
[![Email](https://img.shields.io/badge/Email-8B5CF6?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:erkinqara@proton.me)

</div>

---

## About

Senior Software Engineer at **Technosec.io** (five years) — building a JupyterLab-based econometric/marketing-analytics platform end to end, from a React/TypeScript frontend extension to a Python/Tornado backend. Upstream contributor to JupyterLab and the Jupyter-AI ecosystem.

Open to remote work worldwide, as a contractor (B2B) or via an Employer of Record.

---

## What I'm building

**Datanout** — a notebook-native AI assistant on JupyterLab + Jupyter AI: a LangChain/LangGraph tool-calling agent with human-in-the-loop approval (per-tool allow / deny / ask), a full Model Context Protocol (MCP) client, cross-session memory, and an AST-based code-safety gate on model-generated code.

**Platform work** — primary author of the JupyterLab frontend extension (custom file browser, a dozen-component React/TypeScript design system, the core plugin entry point), a multi-step data-pipeline wizard, a React Flow pipeline-graph editor, and a cross-origin notebook ↔ analytics integration secured with an HMAC-SHA256 authenticated RPC bridge.

---

## Open source

- **JupyterLab core** (15k+ stars) — file-browser select-all fix, merged and shipped in release 4.2.0 ([#16026](https://github.com/jupyterlab/jupyterlab/pull/16026))
- **Jupyter-AI agent stack** — hardened the agent-driven terminal manager against environment-variable injection, with tests ([acp-client #25](https://github.com/jupyter-ai-contrib/jupyter-ai-acp-client/pull/25)); built file/notebook attachment forwarding with path-traversal protection ([#24](https://github.com/jupyter-ai-contrib/jupyter-ai-acp-client/pull/24)); error handling in the Jupyternaut agent loop ([#42](https://github.com/jupyter-ai-contrib/jupyter-ai-jupyternaut/pull/42)); a cross-stack mimetype API field ([jupyter-chat #383](https://github.com/jupyterlab/jupyter-chat/pull/383)). All merged.
- **LiteLLM** (55k+ stars) — streaming decode-error fix, in review ([#22085](https://github.com/BerriAI/litellm/pull/22085))

---

## Projects

- **diffuseai** — Python GenAI image CLI with a verified end-to-end encryption layer (Argon2id, per-file HKDF-SHA256, AES-256-GCM) driving a self-hosted SDXL backend over ComfyUI
- **kishai** — LLM evaluation harness — YAML golden-set suites with deterministic + LLM-as-judge scoring; a GPU-free replay mode gates CI on model regressions
- **dashboard** — Next.js 15 / React 19 business-intelligence dashboard with a typed integration layer and Jest + Playwright visual-regression tests
- **js2tl** — TypeScript CLI inferring a Telegram TL-schema from a JSON sample

---

<div align="center">
<sub>Python · TypeScript · React · JupyterLab · LangGraph · MCP · FastAPI · Security</sub>
</div>
