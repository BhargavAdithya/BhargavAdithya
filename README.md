<div align="center">

# Chandu Bhargav Adithya

**Software Engineer · AI/ML & Full-Stack Development**

Vijayawada, India · [LinkedIn](https://linkedin.com/in/chandu-bhargav-adithya-5752792a0) · [Email](mailto:bhargavshorinryu03@gmail.com)

</div>

---

## About

Final-year B.Tech Information Technology student (VR Siddhartha Engineering College, 2022–2026) building full-stack applications with AI/ML systems embedded in them — not bolted on top. Comfortable across the stack: FastAPI/Flask and Node.js on the backend, React/Next.js on the frontend, and PyTorch/TensorFlow/LangChain for the model and RAG layers in between.

Research experience in deep learning for satellite imagery (published at Springer's SPIN 2025), an internship building autonomous navigation for a drone platform, and a stack of self-directed projects that go from raw idea to deployed product — trained models, working APIs, and live URLs, not just notebooks.

Looking for **Software Engineer**, **AI/ML Engineer**, or **Full-Stack Engineer** roles where I can work across the model-to-product pipeline.

---

## Technical Skills

**Languages:** Python · Java · JavaScript · C++

**Full-Stack:** React, Next.js, Node.js, FastAPI, Flask, REST APIs, Tailwind CSS

**Machine Learning / AI:** PyTorch, TensorFlow, Keras, scikit-learn, CNNs, U-Net, OpenCV, LangChain, LangGraph, RAG pipelines

**Data & Infra:** MongoDB, MySQL, PostgreSQL, Neo4j, Docker, AWS, CI/CD, Vercel, Render

**Core CS:** Data Structures & Algorithms, OOP, System Design, Git, Linux

---

## Selected Projects

### [UniBrain](https://github.com/BhargavAdithya/Unibrain-backend) — Universal Knowledge Intelligence Platform
`FastAPI` `LangGraph` `Neo4j` `Qdrant` `PostgreSQL` `Redis` `React` `TypeScript`

A production-shaped RAG platform that lets an organization ingest heterogeneous documents (PDF, DOCX, Excel, CSV, scanned images via OCR) and query them through conversational chat, semantic search, and a live knowledge graph. The backend runs a multi-stage retrieval pipeline — section-heading match, broad semantic search, sub-query expansion, and full-document fallback — followed by a reranker before a LangGraph agent workflow generates the final answer, so retrieval quality doesn't collapse into a single vector-similarity lookup. Entities and relations extracted from documents are stored in Neo4j for graph-based exploration alongside the vector store in Qdrant. Two-role access model (Super Admin / Viewer) with a themeable React + TypeScript frontend.
Backend: [Unibrain-backend](https://github.com/BhargavAdithya/Unibrain-backend) · Frontend: [Unibrain-frontend](https://github.com/BhargavAdithya/Unibrain-frontend)

### [TalentScout](https://github.com/BhargavAdithya/TALENTSCOUT) — AI-Powered Technical Interview Platform
`FastAPI` `Streamlit` `PostgreSQL` `Groq API (Llama 3.3 70B)`

An automated technical-interview system that generates scenario-based questions tailored to a candidate's declared tech stack and adjusts difficulty based on how they're performing, rather than running a fixed question bank. Answers are scored across weighted criteria (technical accuracy, depth, clarity, practical application) instead of a single pass/fail signal. Because unsupervised online interviews are trivial to cheat on, the platform also enforces its own integrity: live camera monitoring, fullscreen enforcement, blocked dev-tools/shortcuts, and a violation-strike system. Deployed and live at [talentscout-frontend.onrender.com](https://talentscout-frontend.onrender.com).

### [LandCover AI](https://github.com/BhargavAdithya/lulc-dl) — Sentinel-2 Land Cover Segmentation
`PyTorch` `U-Net` `FastAPI` `React` `HuggingFace`

A full-stack geospatial app that takes a raw Sentinel-2 multispectral `.TIF` image and segments every pixel into one of six land-cover classes. The model consumes a 16-channel input — the 13 native Sentinel-2 bands plus computed NDVI, NDWI, and NDBI spectral indices — and uses sliding-window inference to process full-size satellite tiles without downsampling them into uselessness. Model weights and training details are published separately on [HuggingFace](https://huggingface.co/bhargav37/lulc-dl-model), with the app live at [landcover-frontend.vercel.app](https://landcover-frontend.vercel.app). This extends directly on the change-detection work from my Springer publication — same spectral-index foundations, applied to pixel-wise deep learning segmentation instead of threshold-based classification.

### [My AI Persona](https://github.com/BhargavAdithya/My-AI-Persona) — Autonomous Voice & Chat Agent
`FastAPI` `Vapi` `Deepgram` `Gemini 2.5 Flash` `ChromaDB` `Calendly API`

A RAG-grounded agent — reachable by phone call or chat — that answers questions about my background using a retrieval pipeline built from my resume, GitHub repos, and commit history, and can autonomously book an interview slot through the Calendly API with no human in the loop. Built as two coordinated FastAPI services (voice and chat) sharing one retrieval backend, with the voice side wired through Vapi for telephony and Deepgram for speech-to-text. Evaluated on hallucination rate, retrieval precision, and latency rather than shipped untested.

### [FloraVision](https://github.com/BhargavAdithya/floravision) — Plant Storefront
`Next.js 14` `App Router` `Tailwind CSS`

A responsive plant-storefront frontend built on the Next.js App Router with server-side rendering and optimized font loading (`next/font`) to avoid layout shift. Smaller in scope than the projects above — included as evidence of clean component architecture and attention to frontend performance fundamentals, not just backend/ML work.

---

## Experience

**Research and Development Intern** — IIT Tirupati, PNT Research Labs *(Jul 2025 – Nov 2025)*
Built end-to-end PyTorch pipelines training CNN and Transformer-based models to 90%+ accuracy across 10 classes on large-scale imagery datasets; improved generalization by 15% through custom data augmentation and feature selection.

**Software & Robotics Intern** — India Space Lab *(Jun 2025 – Jul 2025)*
Built an AI-based autonomous navigation system for a drone platform with ~92% obstacle-avoidance accuracy in simulation, implementing A* and RRT* path planning with real-time sensor fusion across SolidWorks, ROS, and Gazebo.

---

## Research

**"Change Detection Using Multispectral Remote Sensing for Urban Monitoring"**
International Conference on Signal Processing and Integrated Networks (SPIN), Springer Nature Singapore, 2025 — co-authored, on multispectral satellite change detection using spectral indices, the same foundation later applied in the LandCover AI project above.

---

## Education

**B.Tech in Information Technology** — Velagapudi Ramakrishna Siddhartha Engineering College, Vijayawada *(2022 – 2026)*

---

## Certifications

AWS Certified Cloud Practitioner (AWS) · Programming Essentials in Python (Cisco) · Joy of Computing Using Python (NPTEL)

---

<div align="center">

[LinkedIn](https://linkedin.com/in/chandu-bhargav-adithya-5752792a0) · [Email](mailto:bhargavshorinryu03@gmail.com)

</div>
