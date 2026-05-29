# RLM-Studio: A Recursive Reasoning WEB-IDE

### *Scaling Intelligence Through Recursive Inferencing*

RLM Studio is a production-grade web development environment built to leverage **Recursive Language Models (RLMs)** and **Self-Steering Architectures**. By utilizing the [Scribe-LLM Backend Engine](https://github.com/oldskool978/Scribe-LLM) as its underlying execution layer, RLM Studio transforms the standard "one-shot" generation paradigm into a multi-stage, self-correcting cognitive loop directly within the browser interface.

---

## 🔬 The Science: Beyond Context Windows
Models naturally suffer from **Context Rot**—as prompts grow, logic degrades. RLM Studio implements the structural findings of the whitepaper, **"Recursive Language Models" (arXiv:2512.24601v2)** to overcome these physical constraints.

> *"We propose Recursive Language Models (RLMs), a general inference paradigm that treats long prompts as part of an environment and allows the LLM to programmatically examine, decompose, and recursively call itself over snippets of the prompt."* > — **Zhang et al., 2026**

### The Edge-Compute Paradigm: Unleashing Local Models
Historically, frontier-level reasoning was bounded by the VRAM memory wall, necessitating massive parameter counts for reliable zero-shot execution. RLM Studio substitutes static parametric scaling with dynamic test-time computation and recursive latent refinement. 

Orchestrated by the [Scribe-LLM Core Engine](https://github.com/oldskool978/Scribe-LLM), local micro-models (1B–8B parameters) operating entirely on consumer-grade silicon are decoupled from the burden of structural memorization via Grammar-Constrained Decoding (GCD). When coordinated into a Sequential Monte Carlo (SMC) swarm, these highly quantized local models achieve deep supervision, converging on reasoning efficacies previously restricted to server-class architectures.

### The DisCIPL Paradigm & Self-Steering
RLM Studio integrates the **DisCIPL** framework. Language models themselves drive the decisions for how to structure inference-time computation. A "Planner" model generates a task-specific inference program that is executed by a population of smaller "Follower" models. This allows small, locally deployed models to match or outperform massive frontier models on challenging constrained generation tasks.

---

## 🛠 Features & Architecture

* **Scribe-LLM Engine Integration:** Deep, low-overhead backend orchestration. RLM Studio interfaces natively with the [Scribe-LLM Core Engine](https://github.com/oldskool978/Scribe-LLM) to drive its local hardware execution tracks—including AMD ROCm, NVIDIA CUDA, and high-throughput CPU vectorization—without relying on external cloud dependencies.
* **A Transparent Architecture:** A real-time virtual file system accessible to the model context. Interact directly with the model's internal "Running Buffer." Never guess what the model is thinking; see the Plan, the Critique, and the Evolution of the codebase.
* **Sequential Monte Carlo Swarm Logic:** Active orchestration framework that manages parallel candidate generation paths, pruning low-probability trajectories while steering local weights toward deterministic solutions.
* **Native Inference Controls:** Direct hardware-level control using Mirostat v2 sampling, Context Shift, and JSON-enforced Grammar-Constrained Decoding (GCD) managed directly through the unified backend pipeline.
* **Polystructural Switching:** The engine dynamically reshapes its own output probability space at each stage of the recursion to match the current task layer.
* **PUBA Integration:** Methodologies are strictly enforced to control, isolate, and evaluate privileged reasoning paths within the local execution environment.

---

## 📅 Deployment Roadmap
Following the integration of the core [Scribe-LLM](https://github.com/oldskool978/Scribe-LLM) backend layer, the client UI phase is in its final optimizations.

**Status: [███████████████████▒] 96%**

- [x] Core Scribe-LLM local inference orchestration binding
- [x] Grammar-Constrained JSON schema validation engine
- [x] Sequential Monte Carlo (SMC) swarm orchestration engine
- [ ] Final polishing of the HTML5/CSS3/JS Web-IDE client interface

---

### References
* Zhang, A. L., Kraska, T., & Khattab, O. (2026). *Recursive Language Models*. arXiv preprint arXiv:2512.24601v2. 
* Grand, G., et al. (2025). *Self-Steering Language Models*. arXiv preprint arXiv:2504.07081.
