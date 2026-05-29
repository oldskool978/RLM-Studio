# RLM-Studio: A Context-Managed Codebase Generation & Refactoring Harness

### *Abstract Syntax Tree (AST) Mapping and Recursive Inference Execution Workspace*

RLM-Studio is a web-native, deterministic engineering workspace and verification harness optimized for macroscopic codebase creation, refactoring, and automated structural repairs. Moving away from standard conversational chat frameworks, RLM-Studio handles software codebases as unified execution trees rather than fragmented text sequences. While the layout provides a dedicated sidebar for localized chat interaction and sequential diagnostics, the core workspace operates as an autonomous engineering console. The operator defines high-level programmatic goals or points to targeted code defects, and the system executes file mutations directly across a hermetic filesystem instantiated entirely within the browser client.

The platform coordinates structural context management methodologies established during the development of the [Scribe-LLM Core Engine](https://github.com/oldskool978/Scribe-LLM) to maximize token utility and guide localized inference passes across multi-file architectures.

---

## 🔬 Core Architectural Paradigms

RLM-Studio operates on formal data-transformation loops designed to track code dependencies precisely while protecting against context rot:

### 1. Stateful Recursive Language Model (RLM) Cognitive Loops
*   **Programmatic Context Interaction:** Implementation follows the formal RLM framework, treating long prompts and codebase schemas as an external environment that the underlying model can programmatically query, partition, and modify.
*   **Amnesia-Free REPL Execution:** The system deploys stateful Read-Eval-Print Loops via an integrated `RLMNodeStrategy`. The model runs automated inspection routines over workspace registers and evaluates intermediate adjustments before committing changes.
*   **Automated Convergence Targets:** The cognitive loop runs continuously across file blocks until a deterministic `<status>resolved</status>` token is parsed, signifying semantic completion.

### 2. Hermetic In-Browser Filesystem
*   **Total Local Isolation:** The environment hosts an entirely isolated, browser-accessible Virtual File System (VFS) mapped to episodic memory blocks.
*   **Operator Intermediation:** Operators can move through the virtual directory tree, inspect model-generated file variants, request targeted edits, or manually modify source lines directly within the VFS panels.
*   **One-Click Structural Export:** Once code updates pass validation checks and achieve logical convergence, the operator can click the download action to download the entire workspace folder structure instantly. The filesystem is serialized, packed, and delivered as a clean local project directory ready for production deployment.

### 3. Abstract Syntax Tree (AST) & Context Matrix Controls
*   **Structural Context Compaction:** Rather than feeding raw, high-entropy source text directly into the model's primary window, the harness strips comments and parses structures into high-level semantic tokens.
*   **Inline Context Management:** VRAM allocations and token thresholds are profiled before every generation pass using a real-time `ContextMatrix.enforceContextBounds` workflow.
*   **Autonomous Evacuation Slicing:** When project scopes expand near physical hardware boundaries, the compiler runs isolated micro-passes to condense long conversation histories into dense latent summaries. This keeps critical architectural limits, class blueprints, and core prompt dependencies in the immediate context of the model being leveraged.

### 4. Deterministic DAG Routing
*   **Elimination of Regex Parsing:** Macro-structural workflows are managed through a compiled `DAGLogicEvaluator`. The engine routes token operations through dedicated text classification, file editing, and verification nodes using explicit JSON schemas and GBNF grammar constraints.
*   **Pushdown Lexical Processing:** Output states and syntactic token boundaries are processed character-by-character via a custom `_lexicalStreamParse` setup. The architecture isolates system blocks (`<think>`, `<rlm_exec>`, `<artifact>`) sequentially, avoiding syntax frailty during live token streaming.

---

## 🛠 Features & Harness Workflow

*   **Explorable Virtual File System (VFS):** RLM-Studio displays an interactive folder panel linked straight to Scribe-LLM's internal registers. Operators can visually monitor how the model populates, updates, and splits project code across individual reasoning nodes.
*   **Deterministic Codebase Harnessing:** Designed to track complete software architectures rather than individual code snippets. The application evaluates file footprints, line numbers, and register spaces natively, letting local models cross-reference dependencies accurately across an entire folder layout.
*   **Inline Context Handling & Token Recovery:** Monitors low-level chunk metadata flags directly from the inference gateway socket. If a generation reaches max token constraints, the workspace freezes the transaction state, appends the partial generation as an assistant prefix, and hydrates a dependency-contingent asset map; then executes a continuation pass with no degradation to the task in flight.

---

## 📅 Implementation Roadmap

Following the production deployment of Scribe-LLM v1.0.0's backend core and hardware acceleration modules, integration focus is centered on optimizing the Web-IDE visualization layout and local VFS serialization.

**Status: [███████████████████▒] 96%**

- [x] Bidirectional server-sent event (SSE) state streaming via the `ScribeGateway` matrix.
- [x] Local multi-register `VectorizedVirtualFileSystem` synchronization mechanics.
- [x] Secure, isolated JavaScript Web Worker sandbox for code execution testing.
- [x] Interactive web UI file browser and live directory tracking panels.
- [ ] Final optimization of the browser-based codebase compiler and automated file export.

---

### References
* Zhang, A. L., Kraska, T., & Khattab, O. (2026). *Recursive Language Models*. arXiv preprint arXiv:2512.24601v3.
* Grand, G., et al. (2025). *Self-Steering Language Models*. arXiv preprint arXiv:2504.07081.
* Jolicoeur-Martineau, A. (2025). *Less is More: Recursive Reasoning with Tiny Networks*. (Samsung SAIL Montréal).
* Hamilton, S., & Mimno, D. (2025). *Lost in Space: Optimizing Tokens for Grammar-Constrained Decoding*. (Cornell University).
* DeepSeek-AI. (2025). *DeepSeek-V4: Towards Highly Efficient Million-Token Context Intelligence*.
```
