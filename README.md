# Hrishikesh Yadav (Rishii)

Systems programmer & software engineer working at the intersection of browser engines, verifiable AI systems, distributed inference, and high-performance data runtimes.

[Portfolio](https://rishiicreates.vercel.app) &nbsp;•&nbsp; [Twitter / X](https://x.com/rishiicreates) &nbsp;•&nbsp; [Email](mailto:rishiicreates@gmail.com)

---

### Upstream Open Source Contributions

#### [Servo](https://github.com/servo/servo) — Next-Generation Web Rendering Engine in Rust
- **WebGL2 Texture Bindings ([#49632](https://github.com/servo/servo/pull/49632))**: Handled errors from `active_texture_slot` to eliminate runtime panics on invalid enum queries in WebGL1 contexts, paired with comprehensive Web Platform Tests (WPT).
- **Layout Engine Modernization ([#49415](https://github.com/servo/servo/pull/49415))**: Modernized float geometry and layout test suites, migrating deprecated standard library numeric primitives to modern Rust associated constants.
- **Script & DOM Bindings ([#49637](https://github.com/servo/servo/pull/49637), [#49490](https://github.com/servo/servo/pull/49490), [#49409](https://github.com/servo/servo/pull/49409), [#49328](https://github.com/servo/servo/pull/49328))**: Hardened DOM-to-JS conversions across `Window`, `Document`, and `ServiceWorkerGlobalScope` by threading contextual JS execution contexts and blob URL resolution.
- **IFrame Memory Safety ([#50115](https://github.com/servo/servo/pull/50115))**: Migrated `HTMLIFrameElement` internal mutation paths to `safe_borrow_mut` for borrow-checker safety under dynamic DOM script execution.

#### [Apache DataFusion](https://github.com/apache/datafusion) — Extensible SQL Query Engine in Rust & Arrow
- **Columnar Metadata Preservation ([#26938](https://github.com/apache/datafusion/pull/26938))**: Implemented schema metadata and extension type propagation (UUID, JSON) across `MAX` and `MIN` accumulator implementations in `datafusion-functions-aggregate`, verified via sqllogictest suites.

---

### Featured Systems & Projects

#### [Rawfy](https://github.com/rishiiicreates/rawfy)
*Universal web perception engine for AI agents*
- High-performance engine written in Rust 2021 that converts arbitrary web documents and dynamic DOM into clean, agent-digestible Web Semantic Markdown (WSM), structured JSON, and interactive element maps.
- Native Astral `uvx` zero-setup runner for instant one-line CLI execution without local builds.
- Featured on the [XERJ Corpus Hub](https://hub.xerj.org/contributors/rishiiicreates) as an open-source reference solution for AI coding workflows.

```bash
uvx --from git+https://github.com/rishiiicreates/rawfy.git#subdirectory=python rawfy https://example.com
```

#### [Shiro — Academic AI & RAG](https://github.com/rishiiicreates/shiro-academic-ai)
*Context-aware academic intelligence engine and syllabus retrieval system*
- Specialized retrieval-augmented generation (RAG) platform indexing semester coursework, lecture materials, and academic syllabi.
- Features citation-backed doubt solving, multi-modal note processing, and structured study workflows. Live at [chiroshiro.vercel.app](https://chiroshiro.vercel.app).

---

### Core Focus & Toolkit

- **Systems & Engines**: Rust (2021/2024), C++, WebAssembly, Browser Engines (Servo, Chromium internals), Linux Systems Programming
- **Data & Distributed Systems**: Apache Arrow, Apache DataFusion, High-Throughput Columnar Execution, Distributed Inference, Speculative Decoding
- **AI Infrastructure & Runtimes**: Verifiable LLM Systems, Agent Tooling / MCP Protocols, Tensor Parallelism, PyTorch
- **Web & Interface Architecture**: TypeScript, React, Next.js, Node.js, Tailwind CSS
