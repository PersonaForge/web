# 🎭 PersonaForge — Make Your AI a Master of Role Consistency

> Struggling with LLMs that forget who they are mid-conversation? Tired of hallucinated tone shifts?
> **PersonaForge** gives your AI a stable, evolving persona — one that remembers, reasons, and resonates.

---

## ✅ Roleplay That Doesn't Fall Apart

**PersonaForge** is a full-stack framework built for **character consistency, multi-turn memory, and stylistic stability**.
By combining **LLM + RAG + Rule Engines + Post-Editing + Reranking + Feedback Loops**, it transforms your AI from a vague improviser into a **coherent persona you can trust**.

---

## 🧠 Why PersonaForge?

### 🎯 Ultra-Stable Character Identity

With Character Persona Training (CPT), we extract and maintain a compact, evolving profile for each role — ensuring consistent behavior across long conversations.

### 🔄 Robust Context Memory

Short-term recall + long-term learning using ChromaDB + RAG. The more it talks, the more it remembers — intelligently.

### 🧹 No Nonsense, Just Consistency

With our **Generate–Delete–Rewrite** pipeline, the system surgically removes off-brand output and rewrites it to align with core personality traits.

### 🪞 Self-Refining AI

Self-reflection meets ranking. With **Self-Refinement Loops** and **Ensemble Reranking**, AI learns to judge and improve its own responses in real-time.

### 🧭 Plan Before You Talk

Our **Plan-Then-Execute** strategy lets the model outline first, generate later — reducing hallucinations and improving logical flow.

### 🏢 Multi-Tenant Support

Built-in multi-tenant architecture with data isolation, tenant-specific configuration, usage tracking, and API key authentication.

---

## 💡 Use Cases

* 🤖 AI Agents / Chat Assistants: Maintain a stable tone and personality across conversations.
* 🎮 NPCs / Virtual Characters: Build vivid, believable AI personas that never break character.
* 🧑‍🏫 AI Tutors / Coaches: Deliver consistent tone and perspective tailored to learning journeys.
* 🧘‍♂️ LLM Developers: Modular, explainable, rule-governed — and safe for production.
* 🏢 SaaS Providers: Offer persona generation as a multi-tenant service with usage tracking.

---

## 🚀 Start Building Your Role-Aware AI

Tired of hacking prompts to simulate consistency?
**PersonaForge** gives you one place to define, evolve, and enforce your AI's identity.

# PersonaForge

PersonaForge is a framework for creating consistent AI personas with context-aware memory, rule-based verification, and dynamic prompt engineering.

## Features

- **Durable Rules** for pre/post-prompt verification, ensuring the consistency and compliance of AI responses
- **ChromaDB** vector storage for conversation memory and RAG (Retrieval Augmented Generation)
- **Character Persona Training (CPT)** to continuously extract and refine persona traits from conversations
- **Prompt Decorators** for dynamic prompt enhancement with chain-of-thought reasoning, formatting control, and more
- **Generate-Delete-Rewrite** workflow for post-processing to ensure persona consistency
- **Sequence Normalization** to reduce sensitivity to attribute order in persona descriptions
- **Multiple Candidate Generation** with ensemble reranking to select the most consistent responses
- **Circuit Breaker** pattern for resilient API calls and improved fault tolerance
- **Async Architecture** for efficient handling of LLM calls and API requests
- **Multi-Tenant Support** with data isolation, tenant-specific configuration, and usage tracking
- **Proper Test Coverage** with both mock and real OpenAI API tests
