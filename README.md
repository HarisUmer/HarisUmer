# Muhammad Haris Umer

**AI/ML engineer (Lahore, Pakistan) — I build LLM and agent systems and the Python backends that keep them running.**

Open to full-time AI/ML engineer roles in Lahore and remote · [harisumer58@gmail.com](mailto:harisumer58@gmail.com) · [LinkedIn](https://linkedin.com/in/harisumer1124) · [Portfolio](https://cv-gilt-beta.vercel.app)

---

## What I'm good at

- **LLM applications:** tool calling, agentic RAG, and structured extraction with validated outputs (OpenAI, Anthropic, Gemini).
- **Production backends for AI:** Django, Celery, Redis, and PostgreSQL, including single-writer coordination and WebSockets.
- **Generative and vision pipelines:** Stable Diffusion with ControlNet and IP-Adapter, YOLO and ByteTrack, and homography for queue metrics.

## Selected work

| Project | The problem | What I built | Result | Code |
|---|---|---|---|---|
| **Artikon** (group final-year project) | Characters look different in every AI-generated comic panel | LangGraph pipeline: resolve character, mask, generate, composite, identity check, behind a Next.js app. Stable Diffusion with ControlNet and IP-Adapter. Embedding search over LoRA style tags. | Identity check between panels. No published similarity score yet. | [Repo](https://github.com/HarisUmer/artikon-comic-genai) |
| **Aircraft Parts Quote Automation** | Supplier quotes buried in email threads | Gmail → LLM extraction (Pydantic-validated, OpenAI or Anthropic) → supplier ranking → Google Sheets | Replaces manual inbox review. No published accuracy figure yet. | [Repo](https://github.com/HarisUmer/aircraft-quote-automation) |
| **Visible Electrical Defect Detection** | Open, short, and damage defects in cables and PCBs | YOLOv8n detectors trained on 7,000+ labeled images | 0.888 mAP50 on outdoor cable damage. CLAHE and sharpening raised precision from 0.81 to 0.86 on 484 test images. A screening aid, not a safety certificate. | [Repo](https://github.com/HarisUmer/circuit-fault-vision) |
| **Trading engine coordination** | Races between UI, engines, and the database in a live system | Single-writer manager, Redis and Celery, serialized database writes. Architecture only — no strategy or secrets. | About 6,000 signals/sec (estimated). | [Repo](https://github.com/HarisUmer/trading-engine-redis-architecture) |

**Sortsy** ([sortsy.ai](https://sortsy.ai)) — AI file organizer I contributed to at CoalDev (July 2025 – September 2026). My work was the Django REST API, Celery workers, the PySide6 desktop agent, and Amazon Bedrock captions indexed in Qdrant. [Case study](https://github.com/HarisUmer/sortsy) (no proprietary code).

## Also on GitHub

- [Airport Queue Analytics](https://github.com/HarisUmer/airport-queue-analytics) — YOLO, ByteTrack, and homography for queue length and density. Built at Nexpred.
- [LLM Intake Chatbot](https://github.com/HarisUmer/llm-intake-chatbot) — Gemini tool calling for intake and disputes. Built at Nexpred.
- [Semantic Document Retrieval](https://github.com/HarisUmer/1st_Rag) — BERT embeddings and KMeans chunking compared with fixed-size RAG splits.
- [vedGen](https://github.com/HarisUmer/vedGen) — local premise-to-video pipeline designed for one 12 GB GPU. In progress. No sample film published yet.

## Skills, with where to see them

| Skill | Evidence |
|---|---|
| LLM tool calling and structured outputs | Aircraft Quote Automation, LLM Intake Chatbot |
| Agent orchestration (LangGraph) | Artikon |
| Celery, Redis, PostgreSQL | Trading coordination layer, Sortsy |
| Computer vision (YOLO, tracking, homography) | Airport Queue Analytics, defect detection |
| Diffusion pipelines (Stable Diffusion, ControlNet, IP-Adapter) | Artikon |

<sub>Some of my professional work is private. I only publish what I have permission to publish.</sub>
