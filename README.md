<!-- ============================================================ -->
<!--   PRATHAMESH TAWARE · AI Engineer                            -->
<!--   Profile README: github.com/PrathameshTawar                -->
<!-- ============================================================ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0f172a,35:1e3a8a,70:0891b2,100:06b6d4&text=Prathamesh%20Taware&fontColor=ffffff&fontSize=54&fontAlignY=38&desc=Agentic%20AI%20%E2%80%A2%20LLM%20Systems%20%E2%80%A2%20Backend&descAlignY=58&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&pause=1100&color=06B6D4&center=true&vCenter=true&width=820&lines=AI+Engineer;Multi-agent+systems+with+LangGraph;RAG+%E2%80%A2+evals+%E2%80%A2+guardrails;Multilingual+AI+for+Indian+languages;Python+%E2%80%A2+FastAPI+%E2%80%A2+TypeScript+%E2%80%A2+AWS" alt="Typing intro"/>

<br/>

<a href="https://www.linkedin.com/in/prathamesh-taware-39bab8288"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<!-- TODO: add your email, e.g. <a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a> -->
<img src="https://komarev.com/ghpvc/?username=PrathameshTawar&label=Profile%20views&color=0891b2&style=for-the-badge" alt="Profile views"/>

</div>

---

## 👋 About me

```yaml
name:      Prathamesh Taware
education: Computer Engineering · MIT Academy of Engineering, Pune
focus:     Multi-agent systems · RAG & evaluation · multilingual AI · backend engineering
research:  Indic multilingual RAG translation (paper in progress)
```

I build AI systems that show their work: agents that cite evidence, pipelines that get benchmarked, and backends with tests behind them.

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [SwarmIQ](https://github.com/PrathameshTawar/Vellora-project-)
**A multi-agent AI research assistant.** It automates literature review from start to finish.

- Planner, literature, claim-extraction, conflict-resolution, synthesis and evaluator agents
- Credibility scoring and a knowledge store with memory
- Gradio UI that streams agent activity and exports to MD, PDF, PPT and JSON
- **225 passing unit and property-based tests**

`Python` `OpenAI` `Pinecone` `Tavily` `Gradio`

</td>
<td width="50%" valign="top">

### 👑 [Monarch](https://github.com/PrathameshTawar/aws-benglore)
**An AI incident investigator.** It turns logs, post-mortems, metrics and screenshots into a root-cause report you can trace back to the evidence.

- LangGraph agents with RAG, SQL and an MCP tool server
- Input and output guardrails, evidence chains, contradiction detection
- Built-in evaluation harness
- Groq Vision reads dashboard screenshots

`FastAPI` `LangGraph` `React` `Docker` `AWS S3 + ECS Fargate`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌐 [Indic RAG Translation](https://github.com/PrathameshTawar/translations-)
**Retrieval-augmented translation for Indian languages.** This is the research project behind my paper.

- FAISS retrieval indexes for 7 languages: Hindi, Marathi, Bengali, Gujarati, Kannada, Tamil and Telugu
- Benchmark harness with ablation studies, beam-search profiling, and hallucination and security evaluation
- Flask API with a React front end, deployable with Docker

`Python` `FAISS` `Transformers` `Flask` `React`

</td>
<td width="50%" valign="top">

### 👁️ [Visual AI Agent](https://github.com/PrathameshTawar/visual-agent-)
**A privacy-first browser activity memory.** It records what you do in the browser and makes it searchable with vision AI.

- Chrome extension (Manifest V3, TypeScript) sends events to async FastAPI, with Celery workers for vision, OCR and embeddings
- Semantic and keyword search over pgvector
- Opt-in only, site allow and block lists, and redaction of sensitive fields

`TypeScript` `FastAPI` `Celery` `PostgreSQL + pgvector` `React`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎮 [STRIDE OPS](https://github.com/PrathameshTawar/CS-)
**An AI-native first-person shooter engine that runs in the browser.**

- Two modes: Classic (deterministic) and AI (generated, adaptive levels)
- Entity-component system, squad AI with perception and navigation, procedurally generated meshes, textures and audio
- About 35k lines of TypeScript, with unit tests and a visual-regression gate

`TypeScript` `Three.js` `WebGL2` `Vite`

</td>
<td width="50%" valign="top">

### 📊 [SignalForge](https://github.com/PrathameshTawar/trading-system)
**A quantitative research pipeline for equity markets** (NSE, BSE and US).

- Scale-free feature engineering and IC-based feature selection
- Nested walk-forward cross-validation with embargo purging to prevent data leakage
- Matrix backtesting, drift monitoring, and a paper-trading harness

`Python` `pandas` `scikit-learn` `statsmodels`

</td>
</tr>
</table>

<details>
<summary><b>🧰 More projects</b></summary>
<br/>

| Project | What it is | Stack |
|:--|:--|:--|
| [EngageTech AI](https://github.com/PrathameshTawar/et) | 8-agent LangGraph pipeline that writes social posts that pass compliance checks and get an engagement score. Streams over SSE, with human approval before posting | LangGraph · FastAPI · Qdrant |
| [KYC Intelligence](https://github.com/PrathameshTawar/punawala) | Video-based loan onboarding. Voice and vision checks feed a rule-based risk engine, so AI never makes the final call alone | FastAPI · React · Alembic · K8s |
| [AIM-Env](https://github.com/PrathameshTawar/Reinforcement-learning) | OpenEnv-compliant RL environment where an LLM agent triages an email inbox. Auto-deploys to Hugging Face | Python · Docker · GitHub Actions |
| [Hava](https://github.com/PrathameshTawar/hava) | Speech intelligence: Whisper transcription, translation, AI summaries and live WebSocket transcription | FastAPI · Celery · Next.js |
| [ReviewPulse](https://github.com/PrathameshTawar/27-sept-) | AI code review with health scores, a 3-panel inspector and fix diffs. Works with OpenAI, Ollama or LM Studio | Next.js · NestJS · Prisma |
| [Cursor Reader MCP](https://github.com/PrathameshTawar/wind-testing-) | MCP server that safely reads Cursor workspace metadata. It blocks secret files from being read | TypeScript · MCP |

</details>

---

## 🛠️ Tech stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=python,ts,js,cpp,java,bash&perline=6"/>

**Backend & data**<br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,postgres,redis,mongodb,supabase&perline=7"/>

**AI / ML**<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&perline=3"/>

`LangGraph` `LangChain` `RAG` `FAISS` `pgvector` `Pinecone` `Qdrant` `MCP` `HuggingFace` `Whisper`

**Cloud & DevOps**<br/>
<img src="https://skillicons.dev/icons?i=aws,docker,githubactions,linux,nginx&perline=5"/>

**Frontend & graphics**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,threejs&perline=5"/>

</div>

---

## 📊 GitHub activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=PrathameshTawar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats"/>
<img height="170" src="https://streak-stats.demolab.com?user=PrathameshTawar&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=PrathameshTawar&theme=tokyo-night&hide_border=true&radius=10" alt="Contribution graph"/>

<!-- Generated by .github/workflows/snake.yml (pushed to the "output" branch) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PrathameshTawar/PrathameshTawar/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PrathameshTawar/PrathameshTawar/output/github-snake.svg"/>
  <img width="95%" alt="Contribution snake" src="https://raw.githubusercontent.com/PrathameshTawar/PrathameshTawar/output/github-snake-dark.svg"/>
</picture>

</div>

---

<div align="center">

**Currently:** writing a paper on Indic multilingual RAG · building multi-agent systems · open to AI engineering internships

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,35:1e3a8a,70:0891b2,100:06b6d4&height=110&section=footer" width="100%"/>

</div>
