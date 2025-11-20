# ANM Roadmap (v1.0 → v2.0)

This roadmap outlines the future development goals for the Artificial Neural Mesh (ANM) project. ANM v1.0 currently exists as a conceptual and architectural research release. The next milestones focus on transitioning toward **prototype implementation**, **experimentation**, and **modular model orchestration**.

---

## 🚀 Phase 1 — Prototype Foundations (v1.1)

**Goal:** Establish the core structure of ANM on a local machine.

### Tasks:

* Implement a minimal **Router LLM** using an open-source model.
* Create **dummy Specialist modules** (Coding, Logic, Vision) with small LLMs.
* Implement a basic **message-passing system** that simulates Web-of-Thoughts.
* Integrate simple **Refiner** and **Verifier** models.
* Create a small **vector-based episodic memory** using FAISS or ChromaDB.

---

## 🧠 Phase 2 — Web-of-Thoughts Engine (v1.5)

**Goal:** Build an actual multi-model interaction protocol.

### Tasks:

* Allow specialists to share intermediate reasoning.
* Enable cross-evaluation (specialists checking each other).
* Add turn-based debate mode.
* Store reasoning trails for analysis.
* Implement early conflict-resolution logic.

---

## 🔒 Phase 3 — Safety Core Implementation (v1.7)

**Goal:** Bring the Verifier and routing safety rules to life.

### Tasks:

* Add rule-based safety filters.
* Add factual consistency checks.
* Build a simple harm-prevention layer.
* Implement restricted tool-execution sandbox.
* Add logging + transparency systems.

---

## ⚙️ Phase 4 — Memory & Learning (v1.8)

**Goal:** Functional episodic memory.

### Tasks:

* Store: prompts, outputs, failures, successes.
* Retrieve relevant memory for new tasks.
* Add scoring for specialist usefulness.
* Enable Router to adapt based on historical patterns.

---

## 🧬 Phase 5 — Expansion Engine Prototype (v2.0)

**Goal:** Controlled self-improvement.

### Tasks:

* Identify missing capabilities.
* Auto-collect small open datasets.
* Fine-tune a simple new specialist.
* Connect the specialist to the mesh.
* Require manual approval for expansion.

---

## 🎯 Long-Term Vision (Post-v2.0)

* Hardware-optimized ANM (GPU/TPU/LPU integration).
* Multi-machine mesh for distributed reasoning.
* Stronger Verifier using logical models.
* Robotic planning pipelines.
* Multi-modal specialists (video, sensor fusion, 3D understanding).
* Fully transparent WoT visualization system.

---

## 📌 Summary

ANM v2.0 focuses on shifting from a **pure architecture design** to a **working prototype**. Each stage builds toward a safe, interpretable, multi-model cognitive system built entirely on a single local machine.

You will maintain strict safety, modularity, and transparency at every step — staying true to the ANM principles.
