# Hi, I'm Tiya 👋

Third-year ECE (AI) undergrad at IGDTUW, Delhi · AI/ML engineer in the making · working my way into startups

I build GenAI and NLP systems, real-time backends, and optimization platforms. I learn fastest by building with others and shipping before the deadline.

- 🌱 **Currently**: building **DistribuQ**, a fault-tolerant distributed task scheduler in Go, to get systems-level depth in concurrency.
- 🔭 **Looking for**: startup internships in AI/ML and backend, where I can build real products and own things early.
- 📫 **Find me**: links at the bottom.

## What I'm into

- 🚀 Startups: early-stage products, fast iteration, and shipping
- 🧠 NLP and GenAI: multilingual transformer pipelines, prompt engineering, LLM integration
- 🏗️ Real-time backend systems: FastAPI, Flask, WebSockets
- 📐 Optimization and simulation: linear programming, multi-agent models

## Hackathons

- 🎯 Selected in the top 1% (top 15 out of 1,631 teams) at **Code Cubicle 6.0 (Geekroom)**
- 📸 Selected in the top 1.1% (top 10 out of 879 teams) at the **Pixels to Products Cloudinary AI Hackathon 2026 (HackIndia)**
- 🥇 Selected in the top 6% internationally (250 out of 4,000+ teams) at **FAR AWAY 2026 (Zuup)**

## Recent projects

**Ex-Vero** (Code Cubicle 6.0): 
- Offline-first edge memory layer on Qdrant. Each device runs hybrid dense and BM25 search and on-device RAG with no network. On reconnect it pushes deltas to a hub, which resolves conflicting facts through trust-weighted consensus with a visible confidence score and an explicit DISPUTED state. Stack: Python, FastAPI, Qdrant Edge (qdrant-edge-py 0.8.0, beta), Qdrant Server, fastembed, CLIP, Ollama (qwen2.5:1.5b), React, Vite, TypeScript, Docker.
- Measured in a real 1 CPU / 512 MB container: 0.19% CPU idle, 100.2% under load, ~296 MB RSS. All 10 backend build phases are complete.
[Repo](https://github.com/KA-1205/Ex-Vero)

**Panchnama** (Pixels to Products): 
- Tamper-evident evidence platform for NGO field photos: Ed25519 device signing at capture, server-side signature and SHA-256 re-verification, immutable originals, a SHA-256 audit hash chain, and YOLOv8 + ChangeFormer before/after change metrics. React Native, Fastify, FastAPI, Supabase/Postgres, Cloudinary
- Replaces weeks of manual counting across ~40,000 photos with automated counts. Targets: <10s capture-to-dashboard, <500ms search over 1K assets, <5 min audit verification. Backed by 86 pgTAP assertions and 20 migrations.
[Repo](https://github.com/HackIndiaXYZ/pixels-to-products-cloudinary-ai-hackathon-2026-chaarwizards)

**FreqBridge** (FAR AWAY 2026): 
- Decentralized multi-agent energy market for Japan’s 50Hz/60Hz split grid: each microgrid agent runs a double auction over a fixed 1.2 GW HVDC converter, driven by live Open-Meteo weather; debugged the swing-equation ODE propagation, converter-capacity and agent-count bugs in the clearing engine. Python, FastAPI, WebSockets, SQLite
- Crisis recovery in ~12s vs ~47s for the PID baseline (about 74% faster, 3.9x); EMA flow smoothing cut converter-flow jitter ~4x in testing

**The Second Shift** (Build with Gemini): 
-AI career re-entry coach for women returning to work: skill-gap analysis, job matching and a progress dashboard, using Gemini API and Sentence-Transformers for semantic skill-to-job matching. React, Vite, TypeScript, Tailwind, Gemini API
[Live site](https://thesecondshift.vercel.app/) · [Repo](https://github.com/KA-1205/The-Second-Shift)

**EventGuard**: 
- Real-time Bengaluru traffic incident command platform: built the Flask REST API, a Leaflet.js Map-HUD, and a PuLP multi-objective knapsack engine that allocates scarce police and barricade capacity under budget and coverage constraints. Flask, Leaflet.js, PuLP, Python
- Optimizes dispatch across 15 high-burden police jurisdictions using a 4-month incident registry.
[Repo](https://github.com/TiyaGarg06/EventGuard)

**DistribuQ**: 
- Fault-tolerant distributed task scheduler in Go: Raft-inspired leader election, least-loaded worker dispatch, heartbeat liveness monitoring and orphaned-task reassignment over net/rpc, with a Transport interface so gRPC can be swapped in without touching scheduler logic. Go, net/rpc
- 6 automated tests covering election, re-election, even dispatch and task reassignment on worker failure
[Repo](https://github.com/TiyaGarg06/DistribuQ)

**LipiVerse**: Emotion-preserving multilingual poem translation, built during my GenAI internship at IGDTUW. It covers 3 Indian language pairs, with structured prompt pipelines that reduce semantic drift and keep tone and cultural nuance.

## What I work with

Languages   Python · C++ · C · Go · R · SQL · JavaScript
Backend     FastAPI · Flask · REST · WebSockets
ML / AI     scikit-learn · LightGBM · CatBoost · NLP pipelines · Prompt engineering · Vertex AI
Optimization & Geo   PuLP · NetworkX · OSMnx · Leaflet.js
Tools       Git · Google Cloud Platform


## Beyond code

Deputy Director General, IGDTUW MUN 2026 · Media Head, BHAV Society

## Connect

- [LinkedIn](https://linkedin.com/in/tiya-garg-a72b2931a)
- [Portfolio](https://YOUR-PORTFOLIO-URL)
- [Email](mailto:tiyagarg0706@gmail.com)
