<h1 align="center">Hi, I'm Divyansh Rana</h1>
<h3 align="center">Agentic AI & RAG Engineer · LangGraph · LangChain · MCP · LLM Fine-tuning | MSc AI @ University of Salford</h3>

<p align="center">
  I build production-style LLM systems and measure them: agentic RAG, multi-agent workflows, fine-tuning, evaluation and guardrails.
</p>

<br/>

---

## Featured Projects

| Project | What it does | Measured results | Stack |
|---|---|---|---|
| [**KubePilot**](https://github.com/Divyanshrana01/KubePilot) | Agentic RAG copilot for Kubernetes SRE work. LangGraph router sends queries to hybrid retrieval or a Text2SQL pipeline with a human approval gate before any SQL runs | RAGAS faithfulness **0.775 → 0.867**, context precision **0.370 → 0.465** on a 31-question golden set | LangGraph · FastAPI · Qdrant · BM25 · HyDE · CRAG · Self-RAG · Postgres · Redis · React |
| [**MedScript-AI**](https://github.com/Divyanshrana01/MedScript-AI) | UK clinical decision support: QLoRA fine-tuned Llama-3.1-8B plus hybrid RAG over NICE guidelines | BERTScore F1 **0.90**, ROUGE-L **0.23** (held-out); reranker **13x faster** at equal recall (0.975); 101 unit tests | Unsloth · TRL · QLoRA · DPO · BGE-M3 · Qdrant · MLflow · FastAPI |
| [**DeepEquity**](https://github.com/Divyanshrana01/DeepEquity) | Multi-agent equity research desk: bull and bear agents debate a ticker, a synthesis agent writes a cited note. Custom MCP server for SEC filings, prices, news and transcripts | Precision@5 **0.70 → 0.86**, nDCG **0.71 → 0.85** (dense vs hybrid + rerank, 22 queries); 231 tests | LangGraph · MCP · Groq · pgvector · Redis · FastAPI · GitHub Actions |
| [**multi-agent-research**](https://github.com/Divyanshrana01/multi-agent-research) | Research platform with 4 LangGraph agents, 3-tier serving (semantic cache, pgvector memory, full run), LLM judges and a weekly PyRIT red team | 59 Terraform resources; 30 attack prompts across 8 categories; 132 offline tests | LangGraph · TensorZero · Bedrock Guardrails · pgvector · Redis Streams · Terraform · ECS Fargate |

### Other work

- [**portfolio**](https://github.com/Divyanshrana01/portfolio): personal portfolio site with a 3D avatar and scroll animations (React · TypeScript · Three.js · GSAP)
- [**PageIndex_RAG**](https://github.com/Divyanshrana01/PageIndex_RAG): experiment comparing chunked FAISS RAG with vectorless PageIndex tree retrieval, scored with RAGAS

---

## What I Work With

| Area | Tools |
|---|---|
| Agents | LangGraph, LangChain, MCP (FastMCP), human-in-the-loop |
| Retrieval | Qdrant, pgvector, FAISS, BM25 + RRF, cross-encoder reranking, HyDE, CRAG, Self-RAG |
| Fine-tuning | Unsloth, TRL, QLoRA, DPO, Hugging Face Hub, MLflow |
| Evaluation & safety | RAGAS, LLM-as-judge, LangSmith, PyRIT, llm-guard, Bedrock Guardrails |
| LLMs | OpenAI, Groq, Llama 3.1, TensorZero gateway |
| Backend | Python, FastAPI, SSE, Pydantic, PostgreSQL, Redis |
| Frontend | React, TypeScript, Vite, Tailwind |
| Infra | Docker, Terraform, AWS (ECS Fargate, RDS, ElastiCache), GitHub Actions, uv, pytest |

<p align="center">
  <img src="https://cdn.simpleicons.org/python/3776AB" height="45" width="55" alt="Python" />
  <img src="https://cdn.simpleicons.org/typescript/3178C6" height="45" width="55" alt="TypeScript" />
  <img src="https://cdn.simpleicons.org/fastapi/009688" height="45" width="55" alt="FastAPI" />
  <img src="https://cdn.simpleicons.org/langchain/1C3C3C" height="45" width="55" alt="LangChain" />
  <img src="https://cdn.simpleicons.org/langgraph/1C3C3C" height="45" width="55" alt="LangGraph" />
  <img src="https://cdn.simpleicons.org/modelcontextprotocol/000000" height="45" width="55" alt="MCP" />
  <img src="https://cdn.simpleicons.org/huggingface/FFD21E" height="45" width="55" alt="Hugging Face" />
  <img src="https://cdn.simpleicons.org/pytorch/EE4C2C" height="45" width="55" alt="PyTorch" />
  <img src="https://cdn.simpleicons.org/mlflow/0194E2" height="45" width="55" alt="MLflow" />
  <img src="https://cdn.simpleicons.org/qdrant/DC244C" height="45" width="55" alt="Qdrant" />
  <img src="https://cdn.simpleicons.org/postgresql/4169E1" height="45" width="55" alt="PostgreSQL" />
  <img src="https://cdn.simpleicons.org/redis/FF4438" height="45" width="55" alt="Redis" />
  <img src="https://cdn.simpleicons.org/react/61DAFB" height="45" width="55" alt="React" />
  <img src="https://cdn.simpleicons.org/docker/2496ED" height="45" width="55" alt="Docker" />
  <img src="https://cdn.simpleicons.org/terraform/844FBA" height="45" width="55" alt="Terraform" />
  <img src="https://cdn.simpleicons.org/githubactions/2088FF" height="45" width="55" alt="GitHub Actions" />
  <img src="https://cdn.simpleicons.org/pytest/0A9EDC" height="45" width="55" alt="pytest" />
  <img src="https://cdn.simpleicons.org/git/F05032" height="45" width="55" alt="Git" />
</p>

---

## Contribution Snake

<img src="https://raw.githubusercontent.com/Divyanshrana01/Divyanshrana01/output/snake.svg" alt="Snake animation" />

---

## Connect with me

<div align="center">
  <a href="https://www.linkedin.com/in/divyanshrana991/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo" />
  </a>
  <a href="mailto:divyanshr141@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo" />
  </a>
  <a href="https://www.instagram.com/__divyanshrana/?hl=en" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Divyanshrana01.Divyanshrana01&" />
</div>
