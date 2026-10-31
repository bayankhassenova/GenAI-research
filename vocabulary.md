# GenAI SME Vocabulary & Terminology Dictionary

This dictionary contains key domain-specific terms for Subject Matter Experts (SMEs) working with Generative AI applications.

| Term | Definition in Plain English | Context / Usage |
| :--- | :--- | :--- |
| **Large Language Model (LLM)** | A deep learning model trained on vast text datasets to predict tokens and generate human-like text. | Core engine behind GenAI products like GPT-4 or Claude. |
| **Retrieval-Augmented Generation (RAG)** | A framework that connects an LLM to external vector databases to pull facts before generating a response. | Used to prevent hallucinations and query private company docs. |
| **Vector Embedding** | A numerical representation of text, images, or audio in a high-dimensional mathematical space to measure semantic similarity. | Used by search engines to find conceptually similar documents. |
| **Hallucination** | A phenomenon where an LLM generates plausible-sounding but factually incorrect or fabricated statements. | Primary risk factor requiring guardrails and factual verification. |
| **Prompt Engineering** | The practice of designing and refining context, constraints, and instructions fed into an LLM for optimal outputs. | Essential skill for guiding model behavior without retraining. |
| **Fine-Tuning** | The process of updating internal model weights using specialized datasets to adapt tone, format, or task execution. | Used to customize an existing base model for legal or medical terminology. |
| **Temperature** | A parameter (0.0 to 1.0) controlling the degree of randomness or creativity in LLM output generation. | Low values (0.0–0.2) are used for facts/code; high values (0.7–1.0) for creative writing. |
| **AI Agent** | An autonomous system powered by an LLM that plans, uses tools (APIs), and executes multi-step tasks to achieve a goal. | Used for automated customer workflows and complex system operations. |
| **Guardrails** | Safety rules, filters, and validation checks wrapped around an LLM to block toxic, unsafe, or confidential data leaks. | Crucial for enterprise compliance and AI safety. |
| **Token** | The basic unit of data (characters or sub-words) processed by an LLM during input and output generation. | Dictates API billing costs and context window limits. |
| **Context Window** | The maximum amount of text (measured in tokens) an LLM can read and consider at a single time. | Determines how much document context can be passed in one request. |
| **Zero-Shot Prompting** | Providing a task instruction to an LLM without giving prior examples in the prompt. | Used for standard tasks where the LLM already has strong pretrained knowledge. |
