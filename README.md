<img alt="Snake animation" src="https://raw.githubusercontent.com/Yasinyan23/Yasinyan23/main/github-snake.svg" width="100%" />

<h1 align="center">Hi, I'm Khachatur 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=7C5CFF&center=true&vCenter=true&width=640&lines=Senior+AI+Engineer;Computer+Vision+%C2%B7+3D+Motion+%C2%B7+LLMs;RAG+%C2%B7+Tool-calling+Agents+%C2%B7+MCP;LeetCode+%23229+global+%C2%B7+3%2C276+solved" alt="Senior AI Engineer · Computer Vision · 3D Motion · LLMs · RAG · Agents · MCP" />
</p>

<p align="center">
  <b>I take AI from research prototype to production</b> — computer vision, 3D human motion, LLMs, RAG and agents, built to survive real traffic.
</p>

## 🧠 About me

- 🎥 Building production **computer vision** at **FitWise AI**: match video → 3D human motion reconstruction → 34 biomechanics metrics per gait cycle, **20k+ plays/day** on 30 inference workers.
- 🏦 Previously led AI & backend for **fintech credit decisioning** at Nexa Product Labs: RAG, tool-calling agents over MCP, LLM evaluation — **−52%** manual-review time, **96%** document field accuracy.
- 📜 Co-inventor on a **patent** for automated sprint biomechanics assessment from reconstructed 3D body motion.
- ⚡ **LeetCode #229 global** · 3,276 problems solved, 783 of them Hard.
- 🎓 M.Sc. in Computer Engineering · 8+ years in software, 4+ in production AI.

## 🛠️ Tech stack

**AI / ML**

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv&perline=10" alt="Python, PyTorch, TensorFlow, OpenCV" />
</p>

![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge)
![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0F766E?style=for-the-badge)
![AI Agents](https://img.shields.io/badge/AI_Agents_%C2%B7_Tool_Calling-7C5CFF?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-5B21B6?style=for-the-badge)
![LLM Evals](https://img.shields.io/badge/LLM_Evals-B45309?style=for-the-badge)
![Fine-tuning](https://img.shields.io/badge/Fine--tuning-BE185D?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=for-the-badge)

**Backend & Infra**

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,postgres,redis,kafka,rabbitmq,docker,kubernetes,aws,gcp,terraform,gitlab,linux&perline=12" alt="FastAPI, PostgreSQL, Redis, Kafka, RabbitMQ, Docker, Kubernetes, AWS, GCP, Terraform, GitLab CI, Linux" />
</p>

![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)

## 🚀 Selected work

| Project | What I built | Impact |
|---|---|---|
| **Production CV & 3D Biomechanics Pipeline** · FitWise AI | Detection & tracking, per-frame 3D body reconstruction, gait-cycle segmentation, 34 metrics per cycle | Insights within **3 min** of upload |
| **Scalable AI Inference & Model Serving** · FitWise AI | Long-lived PyTorch workers on Celery + RabbitMQ, GCP, retries and reprocessing | **20k+** plays/day · **~68k** reprocessed in ~3 days |
| **AI Inference Optimization** · FitWise AI | Fixed PyTorch thread oversubscription, SSD-backed I/O, validation against legacy output | **+30–40%** throughput · **0** mismatches |
| **Tool-Calling AI Agent for Credit Reviews** · Nexa | MCP tools, policy retrieval, guardrails, PII redaction, mandatory human approval | **−52%** review handling time |
| **Document Intelligence & LLM Evaluation** · Nexa | Schema-validated extraction, 1,700-case golden set, CI regression gate | **96%** field accuracy · **−45%** cost per case |
| **LLM-Powered Credit Decisioning** · Nexa | RAG over credit policies, pgvector, hybrid search, Pydantic-validated outputs | **−80%** decision time · **50–70k** requests/day |

## 📦 Open source

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Yasinyan23/rag-agent">DocuQuery RAG Agent</a></h3>
      Strictly grounded RAG microservice: cited answers or a deterministic refusal. Multi-format ingestion, token budgeting, SSE streaming, 160 tests.
      <br /><br />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square" alt="ChromaDB" />
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square" alt="OpenAI" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Yasinyan23/ai-moderation-api">AI Moderation API</a></h3>
      Bring-your-own-key moderation across Claude, GPT-4o and Gemini: Fernet-encrypted keys, revocable JWT sessions, a five-strike pipeline.
      <br /><br />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude" />
    </td>
  </tr>
</table>

## 🏆 LeetCode

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Yasinyan23/Yasinyan23/output/leetcode-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Yasinyan23/Yasinyan23/output/leetcode-light.svg" />
  <img alt="LeetCode: global rank #229, 3,276 problems solved" src="https://raw.githubusercontent.com/Yasinyan23/Yasinyan23/output/leetcode-light.svg" />
</picture>

## 📫 Connect

<a href="https://www.linkedin.com/in/yasinyan23pydev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://t.me/yasinyan23"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
<a href="mailto:pepaniank@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://leetcode.com/u/KhachaturPepanian/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
