# Awesome Grounding 🌐⚓

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Grounding.svg)](https://github.com/ishandutta2007/Awesome-Grounding/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

A curated list of awesome grounding techniques, frameworks, and academic research to anchor AI model outputs to verifiable real-world data.

<img src="assets/banner.svg" alt="Awesome Grounding Banner" width="100%" />

</div>

## 📖 Introduction to Grounding in AI

**Grounding** refers to the engineering and theoretical methods used to anchor an AI model’s outputs to verifiable, real-world data. Instead of allowing a Large Language Model (LLM) to generate text solely based on its static training data, grounding forces the system to rely on authoritative reference material. This process significantly reduces **hallucinations** and ensures auditable, fact-based reliability.

AI grounding is generally divided into two main categories: **Practical Enterprise Grounding** (used in production software) and **Theoretical & Cognitive Grounding** (used in AI research and robotics).

---

## 1. Practical Enterprise Grounding (Runtime Methods) ⚙️

These engineering techniques connect LLMs to accurate, real-time, or proprietary information during a live user session.

| Grounding Method | Description | Year First Used | First Paper Link |
| :--- | :--- | :--- | :--- |
| [**Retrieval-Augmented Generation (RAG)**](docs/retrieval_augmented_generation.md) | The system searches external documents, PDFs, or vector databases for relevant context, then feeds that specific data into the prompt along with the user's query. | 2020 | [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401) |
| [**Tool & Function Calling**](docs/tool_function_calling.md) | The AI triggers live APIs, database queries, or external applications (e.g., checking a CRM or live weather data) to pull exact real-time answers. | 2022 | [MRKL Systems](https://arxiv.org/abs/2205.00445) |
| [**Knowledge Graph Grounding**](docs/knowledge_graph_grounding.md) | The model queries a structured graph of entities and explicit relationships (e.g., Ontologies), forcing the AI to follow strict logic rules instead of guessing connections. | 2021 | [QA-GNN: Reasoning with Language Models and Knowledge Graphs](https://arxiv.org/abs/2104.07650) |
| [**Structured Data Lookups**](docs/structured_data_lookups.md) | The system restricts the AI's data access to specific, rigid fields (like a tracking number, SQL database cell, or pricing limit) rather than parsing free-form text. | 2017 | [Seq2SQL: Generating Structured Queries from Natural Language](https://arxiv.org/abs/1709.00103) |
| [**In-Context Prompt Grounding**](docs/in_context_prompt_grounding.md) | Authoritative reference materials, compliance guidelines, or exact examples (few-shot learning) are pinned directly into the system prompt to tightly constrain the AI’s output boundaries. | 2020 | [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) |


---

## 2. Theoretical & Cognitive Grounding 🧠

These research concepts focus on the deeper, systemic ways an artificial agent understands and interacts with physical or abstract reality.

| Grounding Method | Description | Year First Used | First Paper Link |
| :--- | :--- | :--- | :--- |
| [**Symbol Grounding**](docs/symbol_grounding.md) | A foundational cognitive science concept addressing how abstract symbols (like the word "apple") connect to physical meaning, rather than just pointing to other abstract words in a dictionary. | 1990 | [The Symbol Grounding Problem](https://arxiv.org/abs/cs/9906002) |
| [**Embodied & Multimodal Grounding**](docs/embodied_multimodal_grounding.md) | Used in robotics and computer vision, this connects text tokens directly to sensory inputs—such as camera feeds, physics engines, and spatial awareness—allowing the AI to interact with its physical environment. | 2002 | [Learning words from sights and sounds](https://www.socialmachines.media.mit.edu/publications/pdf/CognitiveScience2002.pdf) |
| [**Semantic Grounding**](docs/semantic_grounding.md) | Explored in AI philosophy to measure whether models truly "understand" language. It is broken down into *functional* (internal data patterns), *social* (use in human contexts), and *causal* dimensions (referencing the real world). | 2024 | [Understanding AI: Semantic Grounding in Large Language Models](https://arxiv.org/abs/2403.01188) |
