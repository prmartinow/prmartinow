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
I contribute to open-source developer tools and agent frameworks, resolving edge-case crashes, memory leaks, and performance bottlenecks:

*   **[anomalyco/opencode](https://github.com/anomalyco/opencode)**:
    *   Resolved CORS and host validation blocks for remote LAN client access (PR #35930).
    *   Prevented TUI MaxListenersExceededWarning by configuring explicit event listener limits and cleaning up HMR leaks (PR #35931).
    *   Fixed frontend crashes on direct session routing by resolving lazy-loaded context provider dependencies (PR #35936).
    *   Stabilized CLI help output formatting and resolved slow agent test races in the test suite (PR #35932).
*   **[Dicklesworthstone/coding_agent_session_search (CASS)](https://github.com/prmartinow/coding_agent_session_search)**:
    *   Fixed SQLite Write-Ahead Log (WAL) checkpoint stalls on error-abort paths and during post-publish finalize cycles (PR #319, PR #321).
    *   Retired native ONNX runtime dependencies and the semantic Cargo feature flag to streamline the tool as a lexical search engine (PR #308).
    *   Hardened the indexer against daemon-level OOM crashes by deferring overlong conversation processing and scoping embedding cancellation (PR #298).

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
