# Enterprise RAG & Multi-Agent Applications

Welcome to the official course repository for **Enterprise RAG & Multi-Agent Applications**.

This repo is for **enrolled students only** and contains all code, exercises, templates, and project materials used throughout the course.

🔗 [Course Page (for reference)](https://maven.com/boring-bot/advanced-llm)

---

## How to Use This Repo

- Content is organized **week by week**, aligned with live sessions and project milestones.
- **Google Colab Pro** is the preferred environment for running notebooks.
- You may also **clone the repo locally** and run notebooks using Jupyter or your IDE.
- Each notebook includes its own dependencies via `!pip install` — there is **no global `requirements.txt`**.

---

## Cloning the Repository (Optional)

```bash
git clone https://github.com/yourusername/enterprise-rag-agents.git
cd enterprise-rag-agents
python3 -m venv venv
source venv/bin/activate


## Pre-Requisites Before Starting

To ensure a smooth experience, please complete the following before the course begins:

- Set up a [Google Cloud Platform (GCP) account](https://console.cloud.google.com/)
- Set up an AWS account
- Subscribe to [Google Colab](https://colab.research.google.com/signup) (Pro ~$10/month recommended)
- Sign up on [Ares API – Traversaal.ai](https://www.traversaal.ai/) (free)
- Set up a [Redis Cloud account](https://redis.com/try-free/)

## Weekly Breakdown

### Week 1: Agentic RAG

- Naive RAG vs Agentic RAG
- Agentic RAG Components
- Advanced Agents

📓 `Module01/Agentic_RAG`  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) _(Coming Soon)_

---

### Week 2: AOptimizing and Deploying Large Language Models

- LLM Deployment and Hosting
- Mixture of Experts
- Quantization methods

---

### Week 3: RAG Memory & Semantic Cache

- RAG Memory
- Semantic Cache

---

### Week 4: Knowledge Graphs and Multi-Agent Workflows

- Using knowledge graphs in RAG
- Principles of KG Standardization
- GraphRAG at scale

---

### Week 5: Agents

- Building LLM Agents from scratch
- AI Agents Frameworks - smolagents, AutoGen, etc.

---

### Week 5: Responsible AI

- Guardrails and their impact on production systems

## Technology Stack

This course uses the following tools and services:

| Area                  | Tools / Frameworks                                  |
|-----------------------|------------------------------------------------------|
| **LLM Access**        | Ares API (via Traversaal.ai)                         |
| **Agent Frameworks**  | LangGraph, AutoGen, SmolAgents                       |
| **Vector Search**     | FAISS (Colab), OpenSearch (optional)                |
| **Memory & Caching**  | Redis Cloud (recommended setup)                      |
| **Notebooks**         | Google Colab Pro (preferred), Jupyter (optional)     |
| **Deployments (Optional)** | AWS Lambda, Step Functions, FastAPI            |
| **Graph Systems**     | NetworkX, LangGraph                                  |
| **Language**          | Python 3.10+                                         |

> You don’t need to pre-install anything locally.  
> All key dependencies are included in each notebook.

---

## Student Feedback (Beta Cohort)

> “Finally a course that moves past theory and teaches **how to build AI systems that work**.”  
> “Everything was practical — I now know how to apply RAG and agents in real products.”

---

## Important

This repository is for **personal educational use only**.  
Please **do not share, redistribute, or publish** any materials externally without written permission.

---

## Let’s Build AI Systems That Survive the Real World

**Your instructor**: [Hamza Farooq](https://www.linkedin.com/in/hamzafarooq/)  
**Created with ♥ by** [boring-bot](https://maven.com/boring-bot)