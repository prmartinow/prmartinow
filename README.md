# Hi there, I'm Pierre Martinow
*Building local-first, privacy-respecting AI tooling for coding agents.*

---

### What I'm Building
I focus on context engineering, agent memory, repository intelligence, and browser automation to make coding agents faster, smarter, and fully local.

*   **[repo-analysis-workbench](https://github.com/prmartinow/repo-analysis-workbench)**: A standalone workbench for evaluating and indexing codebases using local semantic embeddings and reranking.
*   **[web-osint-platform](https://github.com/prmartinow/web-osint-platform)**: Visible Chromium/Rebrowser automation architecture backed by VNC/noVNC display observability.
*   **[wispr](https://github.com/prmartinow/wispr)**: Local voice-to-text pipeline and paste gateway designed for hands-free coding agent dictation.

---

### Contributions
I contribute to open-source developer tools and agent runtimes:

*   **[anomalyco/opencode](https://github.com/anomalyco/opencode)**: Resolved LAN CORS restrictions, fixed frontend session route hydration crashes, corrected TUI event listener leaks, and stabilized test suite execution.
*   **[coder/agent-tty](https://github.com/coder/agent-tty)**: Propagated active session state and environment flags (`sessionId` and `AGENT_TTY_ACTIVE`) to spawned processes.

---

### Key Learnings & Focus Areas
Over the last couple of months developing AI agent systems, I've spent my time on:
*   **Context Engineering:** Pruning code trees, mapping repository structures, and optimizing input tokens for local models.
*   **Local Inference Pipelines:** Deploying and benchmarking embedding/reranking APIs (like Qwen) and local OCR systems (PaddleOCR) on private setups.
*   **Agent TTY and Session Tracing:** Building asciicast rendering tools to record and check semantic traces of agent terminal actions.
*   **Data Ingestion & Sinks:** Streaming agent telemetry using ClickHouse and Redpanda.

---

### Tech Stack & Tools
*   **Languages:** Rust, TypeScript, Python, Bash, Go
*   **Databases & Ingestion:** SQLite, ClickHouse, Qdrant, Redpanda/Kafka
*   **AI Infrastructure:** Local embeddings, Tantivy, Qwen LLMs, Rebrowser, Playwright
*   **DevOps:** Docker, systemd, WireGuard, VLAN bridging

---

**Get in Touch:** [Pierre.Martinow@gmail.com](mailto:Pierre.Martinow@gmail.com)
