# Awesome-Grounding
## Grounding in Artificial Intelligence

**Grounding** refers to the methods used to anchor an AI model’s outputs to verifiable, real-world data. Instead of allowing a Large Language Model (LLM) to generate text solely based on its static training data, grounding forces the system to rely on authoritative reference material. This process significantly reduces **hallucinations** and ensures auditable, fact-based reliability.

AI grounding is generally divided into two main categories: **Practical Enterprise Grounding** (used in production software) and **Theoretical & Cognitive Grounding** (used in AI research and robotics).

---

## 1. Practical Enterprise Grounding (Runtime Methods)

These engineering techniques connect LLMs to accurate, real-time, or proprietary information during a live user session.

* **Retrieval-Augmented Generation (RAG):** The system searches external documents, PDFs, or vector databases for relevant context, then feeds that specific data into the prompt along with the user's query.
* **Tool & Function Calling:** The AI triggers live APIs, database queries, or external applications (e.g., checking a CRM or live weather data) to pull exact real-time answers.
* **Knowledge Graph Grounding:** The model queries a structured graph of entities and explicit relationships (e.g., Ontologies), forcing the AI to follow strict logic rules instead of guessing connections.
* **Structured Data Lookups:** The system restricts the AI's data access to specific, rigid fields (like a tracking number, SQL database cell, or pricing limit) rather than parsing free-form text.
* **In-Context Prompt Grounding:** Authoritative reference materials, compliance guidelines, or exact examples (few-shot learning) are pinned directly into the system prompt to tightly constrain the AI’s output boundaries.

---

## 2. Theoretical & Cognitive Grounding

These research concepts focus on the deeper, systemic ways an artificial agent understands and interacts with physical or abstract reality.

* **Symbol Grounding:** A foundational cognitive science concept addressing how abstract symbols (like the word "apple") connect to physical meaning, rather than just pointing to other abstract words in a dictionary.
* **Embodied & Multimodal Grounding:** Used in robotics and computer vision, this connects text tokens directly to sensory inputs—such as camera feeds, physics engines, and spatial awareness—allowing the AI to interact with its physical environment.
* **Semantic Grounding:** Explored in AI philosophy to measure whether models truly "understand" language. It is broken down into *functional* (internal data patterns), *social* (use in human contexts), and *causal* dimensions (referencing the real world).
