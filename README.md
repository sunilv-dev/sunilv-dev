# Sunil V

### AI Engineer & Full-Stack Developer

**14+ years shipping production software. Now building applied-AI products — and the full-stack platforms that hold them up.**

[🌐 Portfolio](https://sunilv.dev) · [📄 Resume (PDF)](https://sunilv.dev/files/sunil-v-resume.pdf) · [✉️ Email](mailto:sunilv@tuta.io) · [🦊 GitLab — where I actually work](https://gitlab.com/sunil.v)

> *My real body of work lives on GitLab. GitHub is where I keep the shop window.*

---

## 🏆 The Showcase

Three things I've built that I'm happy to be judged by:

### 1. Firsthand — chat with your medical records, on your phone, offline
A local-first RAG app where **your data never leaves the device**. OCR in, embeddings indexed locally, answers out — all offline on a phone.

- On-device RAG: OCR → chunking → local vector index → retrieval-augmented chat
- Runs quantized small LLMs (Qwen2.5 GGUF) through `llama.rn`
- Privacy isn't a feature; it's the architecture
- [GitLab](https://gitlab.com/sunilv/firsthand) · [Codeberg](https://codeberg.org/sunilv/firsthand) · *Play Store / F-Droid: coming soon*

### 2. Serverless facial recognition — 1M+ matches a month, under 500ms
Event photo retrieval at scale. L2-normalized embeddings, HNSW indexing in Redis, auto-scaling serverless infrastructure.

- **<500ms** across 10K+ face comparisons
- **1M+ monthly requests** at **$0.0002 per match**
- Built to be fast, cheap, and boring — the best kind of infrastructure

### 3. Agentic content pipeline — six nodes, one orchestrator
At Boolean & Beyond: a Haystack pipeline (Discover → Strategy → Produce → Distribute → Analyze → Compound) with a RAG layer on Postgres + pgvector, isolating four knowledge types behind member-scoped filters.

- Guards against hallucinated claims and off-voice output
- Durable cross-node orchestration, LLM work kept inside each node
- Human-in-the-loop by design, not by afterthought

---

## ⚡ The Numbers

| | |
| --- | --- |
| **14+ years** | production software, end to end |
| **67%** | inventory-planning productivity gain at Western Digital |
| **1M+** | monthly face matches, sub-500ms |
| **17ms** | Solr query speed across ~25K face encodings |
| **4 hours** | continuous live ABR HLS broadcasts handled |

---

## 🛠 The Toolkit

- **AI / LLM:** LangChain, Haystack, RAG architecture, hybrid retrieval, pgvector, Langfuse, human-in-the-loop design, Hugging Face Inference API
- **On-device AI:** quantized GGUF, `llama.cpp` / `llama.rn`, on-device embeddings, privacy-by-design
- **Backend & Infra:** Python, FastAPI, Django, AWS Lambda / API Gateway / SQS, Redis (HNSW), Docker, serverless
- **Frontend:** React.js, React Native

---

## ☯ A Few Things I've Learned (in English, I promise)

- **The best code is like water.** It doesn't fight the obstacle — it finds the path around it, and after enough time it wears the rock down. I've spent 14 years learning to stop pushing code uphill.
- **To gain knowledge, add things. To gain wisdom, delete them.** Half of senior engineering is knowing what *not* to build, what *not* to index, and which dependency you don't actually need.
- **The tool that announces itself is rarely the one doing the work.** Good infrastructure should be boring. If you notice it, something's wrong.
- **Sustainable beats heroic.** 4-7-8 breathing and Pomodoro aren't wellness garnish — they're why the output stays high for years, not months.

---

## 🌱 Off the Clock

I build small, deliberately odd tools. **Bookmark Rot** is a Firefox add-on whose bookmarks quietly expire if you don't use them — a 30-day trial that doubles each time you reopen it, then deletes itself. *A gentle reminder that hoarding isn't the same as keeping.*

---

<sub>💼 Open to **AI Engineer**, **Full-Stack**, and **Backend** roles.
Paste a job description at [sunilv.dev](https://sunilv.dev) — it'll show you where I match, and honestly, where I don't. *The Tao doesn't flatter, and neither does that tool.*</sub>
