# Unit 4: Multimodal Models, Agentic Workflows & LLM Evaluation

This unit covers the frontier of applied AI: multimodal perception, autonomous agent systems, and the rigorous evaluation and responsible deployment of LLMs.

---

## Notebooks

### 1. Multimodal Models
- **Why Multimodal?** Shared embedding spaces vs. unimodal pipelines
- **CLIP**: Contrastive learning, zero-shot image classification, image-text similarity scoring
- **BLIP**: Image captioning, Visual Question Answering (VQA)
- **Whisper**: Speech-to-text transcription, language detection
- **Pipeline**: Audio → Whisper → CLIP image search → BLIP caption

### 2. Agentic Workflows
- **ReAct Loop**: Think → Act → Observe → repeat
- **Design Patterns**: Reflection, Tool Use, Planning, Multi-Agent Collaboration
- **AutoGen**: `ConversableAgent`, function registration, Researcher → Writer → Translator pipeline
- **CrewAI**: `Agent`, `Task`, `Crew`, `@tool` decorator, same pipeline rebuilt with roles
- **Devyan**: 4-agent software development pipeline (Architect → Programmer → Tester → Reviewer)

### 3. Evaluation, Data, Ethics & Trends
- **DeepEval**: `LLMTestCase`, `AnswerRelevancyMetric`, `FaithfulnessMetric`, threshold-based testing
- **TruLens**: RAG Triad (Context Relevance, Groundedness, Answer Relevance), leaderboard
- **Data Behind LLMs**: Pre-training data sources, quality pipeline, instruction datasets, deduplication
- **LLM Ethics**: Bias demonstration, fairness frameworks, EU AI Act tiers
- **LLM Security**: Prompt injection demo, defense strategies, responsible AI principles
- **Recent Developments**: Reasoning models (DeepSeek-R1 via Groq), SLMs, frontier trends

---

## Assignment

- **Assignment: Evaluated Agentic RAG System**: Build a multi-agent system that retrieves information, generates answers, evaluates them with DeepEval, and retries if quality is below threshold.