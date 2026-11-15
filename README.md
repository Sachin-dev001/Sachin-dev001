<div align="center">

# SACHIN SHARMA
### **AI & Agentic Systems Engineer**

<p align="center">
  <a href="https://agile-mauve-8p7v0p2.tmp.now/"><img src="https://img.shields.io/badge/🌐_Live_3D_Portfolio-agile--mauve--8p7v0p2.tmp.now-10b981?style=for-the-badge&logoColor=white" alt="Live Portfolio" /></a>
  <a href="https://github.com/Sachin-dev001/ai-engineer-ats-resume/raw/main/Sachin_Sharma_AI_Engineer_Resume.pdf"><img src="https://img.shields.io/badge/📄_ATS_Resume-Download_PDF-ffffff?style=for-the-badge&logoColor=black" alt="ATS Resume" /></a>
  <a href="https://linkedin.com/in/sachin-sharma-659ab53b6"><img src="https://img.shields.io/badge/LinkedIn-Sachin_Sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:Sachin.Sharma.37919@gmail.com"><img src="https://img.shields.io/badge/Email-Direct_Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <b>🟢 Open to Work: AI Engineer &bull; Agentic AI Engineer &bull; Applied ML Engineer</b><br>
  <i>Jaipur, Rajasthan, India &bull; Remote Friendly</i>
</p>

---

> *"Production-grade engineering, AI-accelerated where it counts, bespoke where it matters."*

</div>

---

## ⚡ Executive Summary

Specialized **AI & Agentic Systems Engineer** focused on bridging the gap between fragile LLM proofs-of-concept and resilient production infrastructure. Experienced in architecting **low-latency hybrid RAG pipelines**, **stealth browser automation agents with human-in-the-loop (HITL) safeguards**, and **quantitative LLM evaluation suites**.

- 🎯 **Sub-800ms Streaming TTFT:** Real-time token streaming with FastAPI SSE and Gemini 2.5 Flash.
- 📈 **+28% Context Precision Lift:** Mitigating retrieval degradation using BAAI Cross-Encoder rerankers across 5,000+ vector chunks in Qdrant.
- 🛡️ **Zero Bot Detection Bans:** Stealth Playwright browser agents executing 50+ automated portal submissions daily with Gaussian keystroke jitter and CDP flag stripping.
- 🔬 **Quantitative Evals:** Eliminating vibes-based prompting through Ragas, DeepEval, and golden domain benchmark sets.

---

## 🏗️ System Architecture Blueprints

### 1. Timestamp-Aware Video RAG Pipeline (`VideoSage AI`)
```text
[Multi-Hour Video] ──> [Speaker Pause Windowing] ──> [Dense Embeddings]
                                                             │
                                                             ▼
[User Query] ────────> [Qdrant HNSW Vector Search] ──> [Top-20 Chunks]
                                                             │
                                                             ▼
                                                    [BAAI Cross-Encoder]
                                                    (Demotes Distractors)
                                                             │ (+28% Lift)
                                                             ▼
[FastAPI 60 FPS SSE] <── [Gemini 2.5 Flash] <── [Top-3 Re-ranked Context]
```

### 2. Autonomous Stealth Web Application Agent (`AutoApply`)
```text
[Candidate Resume] ──> [Gemini Flash Parser] ──> [Skills & Role Matcher]
                                                             │
                                                             ▼
[Job Portal Navigation] <── [Playwright Stealth Profile (CDP Masked)]
          │
          ├──> [Screening Question Match] ──> [Recruiter Memory Vault] (Auto-Fill)
          │
          └──> [Ambiguous Gate Detected] ──> [Telegram HITL Webhook]
                                                        │
                                                        ▼
                                              [Human Operator: YES/NO]
                                                        │
                                                        ▼
[Portal Submission Confirmed (0 Bot Flags)] <─── [Approved Callback]
```

---

## 📊 Quantitative Production Benchmarks

| Metric / Dimension | Baseline (Naive) | Production Implementation | Quantitative Impact |
| :--- | :--- | :--- | :--- |
| **Retrieval Context Precision** | 64.1% (Cosine Only) | **92.4% (BAAI Cross-Encoder)** | **+28.3% Precision Lift**; distractor chunks filtered |
| **Time-To-First-Token (TTFT)** | 1,850ms | **<800ms (FastAPI SSE)** | Sub-second real-time streaming response |
| **Application Processing Time** | 15 mins / job | **2.2 mins / job** | **85% reduction** in manual workflow latency |
| **Anti-Bot Evasion Rate** | 25% Flagged (Raw Selenium) | **0 Flags (Playwright Stealth)** | **100% success rate** with Gaussian typing jitter |
| **Hallucination Mitigation** | 18% Drift | **<3% Drift (Grounded Citations)** | Exact timestamp citations `[mm:ss]` bound to video |

---

## 🛠️ Technical Stack Matrix

<table>
  <tr>
    <td align="center" width="20%"><b>Generative AI & LLMs</b></td>
    <td>LangChain, LangGraph, Context Engineering, Prompt Engineering, Google Gemini 2.5 Flash, Claude API, OpenAI API, Function Calling</td>
  </tr>
  <tr>
    <td align="center"><b>Vector Search & DBs</b></td>
    <td>Qdrant (HNSW Indexing), ChromaDB, FAISS, BAAI Cross-Encoder Rerankers, Dense + Sparse Hybrid Search</td>
  </tr>
  <tr>
    <td align="center"><b>Agentic Automation</b></td>
    <td>Playwright Stealth, Browser CDP Fingerprint Masking, Gaussian Keystroke Jitter, Telegram Bot API (HITL Webhooks), Supabase RLS</td>
  </tr>
  <tr>
    <td align="center"><b>Evals & LLMOps</b></td>
    <td>Ragas, DeepEval, RAG Triad Benchmarking (Precision, Faithfulness, Relevance), NeMo Guardrails, Regression Eval Suites</td>
  </tr>
  <tr>
    <td align="center"><b>Inference & Serving</b></td>
    <td>FastAPI (Async SSE Streaming), 4-bit Quantization (AWQ/GGUF), Ollama, Time-To-First-Token (TTFT) Tuning</td>
  </tr>
  <tr>
    <td align="center"><b>Backend & Cloud</b></td>
    <td>Python 3.12, PostgreSQL (Supabase RLS), Docker Microservices, Streamlit Cloud, Vercel Edge, Git CI/CD, Linux</td>
  </tr>
</table>

---

## 🌟 Featured Flagship Repositories

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🚀 <a href="https://github.com/Sachin-dev001/ai-portfolio">ai-portfolio</a></h3>
      <p><b>Neo-Brutalist Liquid-Glass 3D Portfolio</b></p>
      <ul>
        <li>Reverse-engineered from award-winning <code>awmedia.marketing</code> design system.</li>
        <li>Features 3D architecture console, live SSE log streamer, interactive evals lab, and 100% mobile viewport responsiveness.</li>
      </ul>
      <p>
        <a href="https://agile-mauve-8p7v0p2.tmp.now/"><img src="https://img.shields.io/badge/Live_Site-Vercel_Edge-black?style=flat-square&logo=vercel" /></a>
        <img src="https://img.shields.io/badge/React_19-Vite_8-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Tailwind_v4-Liquid_Glass-emerald?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎥 <a href="https://github.com/Sachin-dev001/video-sage-ai">video-sage-ai</a></h3>
      <p><b>Timestamp-Aware Conversational Video RAG</b></p>
      <ul>
        <li>Indexes multi-hour YouTube transcripts across 5,000+ vector chunks in Qdrant.</li>
        <li>Combines dense embeddings with BAAI cross-encoder reranking (+28% precision lift) and sub-800ms streaming TTFT via Gemini 2.5 Flash.</li>
      </ul>
      <p>
        <a href="https://video-sage-ai.streamlit.app"><img src="https://img.shields.io/badge/Live_App-Streamlit_Cloud-FF4B4B?style=flat-square&logo=streamlit" /></a>
        <img src="https://img.shields.io/badge/Qdrant-HNSW_Vector_DB-dc2626?style=flat-square" />
        <img src="https://img.shields.io/badge/Gemini_Flash-Sub--800ms-orange?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/Sachin-dev001/ai-job-agent">ai-job-agent</a></h3>
      <p><b>Autonomous Stealth Web Application Agent</b></p>
      <ul>
        <li>Multi-platform stealth automation for Wellfound & Naukri utilizing Playwright stealth with Gaussian keystroke jitter (zero bot flags).</li>
        <li>Features a Human-In-The-Loop Telegram bot webhook and Recruiter Q&A Memory Vault.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Playwright_Stealth-Zero_Bans-green?style=flat-square" />
        <img src="https://img.shields.io/badge/Telegram_Bot-HITL_Webhook-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Supabase-Auth_%26_RLS-emerald?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📄 <a href="https://github.com/Sachin-dev001/ai-engineer-ats-resume">ai-engineer-ats-resume</a></h3>
      <p><b>ATS-Compliant AI Engineer Resume Suite</b></p>
      <ul>
        <li>Production-tested Jake's Resume LaTeX template and single-column clean Markdown format.</li>
        <li>Engineered specifically for Workday, Greenhouse, Lever, and Ashby ATS parsers.</li>
      </ul>
      <p>
        <a href="https://github.com/Sachin-dev001/ai-engineer-ats-resume/raw/main/Sachin_Sharma_AI_Engineer_Resume.pdf"><img src="https://img.shields.io/badge/Resume_PDF-ATS_Verified-success?style=flat-square" /></a>
        <img src="https://img.shields.io/badge/Format-Single_Column_LaTeX-blueviolet?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

## 🎓 Education & Government Credentials

- **Bachelor of Technology (B.Tech) in Computer Science & Engineering**  
  *Poornima University, Jaipur, Rajasthan, India* &bull; **Graduating 2026**  
  *Core Coursework:* Data Structures & Algorithms, Artificial Intelligence, Database Management Systems (DBMS), Operating Systems, Software Engineering.
- **Certificate in Artificial Intelligence & Data Science**  
  *Skill India (**Government of India / NSDC**)* &bull; **Certified 2026**  
  *Accreditation:* National Skill Development Corporation government certification in AI architectures, Machine Learning, Deep Learning models, and data science pipelines.

---

## 📈 GitHub Activity & Engineering Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sachin-dev001&show_icons=true&theme=tokyonight&hide_border=true&bg_color=06070a&title_color=10b981&icon_color=10b981&text_color=d4d4d8" alt="Sachin's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sachin-dev001&layout=compact&theme=tokyonight&hide_border=true&bg_color=06070a&title_color=10b981&text_color=d4d4d8" alt="Top Languages" />
</div>

---

<div align="center">
  <b>Let's build production AI systems that don't break.</b><br>
  <a href="mailto:Sachin.Sharma.37919@gmail.com">Sachin.Sharma.37919@gmail.com</a> &bull; <a href="https://linkedin.com/in/sachin-sharma-659ab53b6">LinkedIn</a> &bull; <a href="https://agile-mauve-8p7v0p2.tmp.now/">Portfolio</a>
</div>
