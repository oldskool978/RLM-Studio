# RLM-Studio: A Recursive Reasoning WEB-IDE

### *Scaling Intelligence Through Recursive Inferencing*

RLM Studio is a production-grade development environment built to leverage **Recursive Language Models (RLMs)** and **Self-Steering Architectures**. RLM Studio transforms the standard "one-shot" generation paradigm into a multi-stage, self-correcting cognitive loop.

---

## 🔬 The Science: Beyond Context Windows
Models sometimes suffer from **Context Rot**—as prompts grow, logic degrades. RLM Studio implements the findings of the whitepaper, **"Recursive Language Models" (arXiv:2512.24601v2)** to overcome these physical constraints.

> *"We propose Recursive Language Models (RLMs), a general inference paradigm that treats long prompts as part of an external environment and allows the LLM to programmatically examine, decompose, and recursively call itself over snippets of the prompt."* > — **Zhang et al., 2026**

### The Edge-Compute Paradigm: Unleashing Local Models
Historically, frontier-level reasoning was bounded by the VRAM memory wall, necessitating massive parameter counts for reliable zero-shot execution. RLM Studio substitutes static parametric scaling with dynamic test-time computation and recursive latent refinement. 

Micro-models (e.g., 1B-8B parameters) operating entirely on consumer-grade silicon are decoupled from the burden of structural memorization via Grammar-Constrained Decoding (GCD). When orchestrated into a Sequential Monte Carlo (SMC) swarm, these highly quantized local models achieve deep supervision, converging on reasoning efficacies previously restricted to >70B server-class architectures.

### The DisCIPL Paradigm & Self-Steering
RLM Studio integrates the **DisCIPL** framework. Language models themselves drive the decisions for how to structure inference-time computation. A "Planner" model generates a task-specific inference program that is executed by a population of smaller "Follower" models. This allows small models to match or outperform massive frontier models on challenging constrained generation tasks.

### HOW RLM-Studio is Different:
* **JSON-Native Epistemology:** The engine operates on rigid JSON schemas to govern the cognitive loop, replacing prompt-based roleplay with deterministic, grammatical constraints.
* **Inference-Time Scaling:** Instead of relying solely on static training, we scale compute during generation, coordinating test-time computation via external algorithms like Sequential Monte Carlo (SMC).
* **Arbitrary Scaling:** Process inputs up to two orders of magnitude beyond standard model context windows.
* **PUBA Integration:** Methodologies are strictly enforced to control and evaluate privileged reasoning paths within the execution environment.

---

## 🛠 Features
* **A Transparent Architecture:** Real-time virtual file system accessible to model context. Interact directly with the model's internal "Running Buffer." Never guess what the model is thinking; see the Plan, the Critique, and the Evolution of the code.
* **Native Llama.cpp Integration:** Direct hardware-level control using Mirostat v2 sampling, Context Shift, and JSON-enforced Grammar-Constrained Decoding (GCD).
* **Web-Native Architect IDE:** Custom-tuned logic is optimized specifically for the HTML5/CSS3/JS stack.
* **Polystructural Switching:** The engine dynamically reshapes its own output probability space at each stage of the recursion to match the current task.

---

## 📅 Coming Soon
We are currently in the final phases of implementation...

**Status: [██████████████████▒▒] 90%**

---

### References
* Zhang, A. L., Kraska, T., & Khattab, O. (2026). *Recursive Language Models*. arXiv preprint arXiv:2512.24601v2. 
* Grand, G., et al. (2025). *Self-Steering Language Models*. arXiv preprint arXiv:2504.07081.
