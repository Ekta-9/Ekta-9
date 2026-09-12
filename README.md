<div align="center">

# Ekta Harde

Turning real-world problems into working code.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ektah/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Ekta-9)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/Ekta_9/)
[![Codeforces](https://img.shields.io/badge/Codeforces-%231F8ACB.svg?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/ektaharde)
[![Gmail](https://img.shields.io/badge/Email-ektaharde%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ektaharde@gmail.com)

</div>

---

I build systems where AI/ML meets backend engineering. Training models, building RAG pipelines and autonomous agents, wiring them into secure APIs, and shipping things that actually hold up in production. Always looking to contribute to something impactful.
---

## Tech Stack

**Languages:** Python · SQL

**AI / ML:** PyTorch · TensorFlow · Scikit-learn · Keras · NumPy · Pandas · Matplotlib · CNNs · Transformers · OpenCV · Image Processing · NLP

**Generative AI:** LLMs · Context Engineering · RAG · LangChain · Ollama · ChromaDB · Hugging Face

**Backend & Databases:** FastAPI · REST APIs · PostgreSQL · Redis

**Tools & Cloud:** Docker · Git · AWS · Postman · Hugging Face Spaces

---

## Projects

### HeartTrace — Congenital Heart Defect Screening
`Java` `Spring Boot` `FastAPI` `PostgreSQL` `PyTorch` `Docker`

A full-stack screening platform for detecting congenital heart defects (Normal / ASD / VSD) from chest X-rays,
built with production-grade security since it handles patient data.

- Custom dual-branch **ConvNeXt-Base** classifier — **82.6% accuracy · 0.83 macro F1**
- FastAPI inference service integrated with a Spring Boot backend exposing **24 REST APIs** over PostgreSQL (Supabase)
- JWT auth, per-record RBAC (owner/editor/viewer), and envelope encryption — AES-GCM for patient data + RSA-OAEP key wrapping with session-scoped key caching
- S3-compatible storage (Supabase Storage in prod, MinIO in dev); deployed via Docker, Render, Vercel, and Hugging Face Spaces

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Ekta-9/CHD-Project)<!-- replace with exact repo URL --> [![Demo](https://img.shields.io/badge/Live%20Demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://chd-for-epics.vercel.app/main.html)<!-- replace with exact demo URL -->

---

### Legal Document Simplifier
`Python` `FastAPI` `Groq LLM` `sentence-transformers` `PyMuPDF` `Docker`

An async pipeline that turns dense legal contracts into plain-language summaries, tuned to minimize LLM cost and re-processing.

- Async FastAPI pipeline parsing PDF/DOCX/text contracts into clauses via a job-based background workflow with a polling frontend
- Cut LLM calls per document **6×** by batching Groq requests with concurrency control and rate-limit backoff
- SQLite clause cache eliminating repeat calls entirely on identical re-uploads
- Self-check-and-retry verification, glossary retrieval via sentence-transformers, readability scoring, and an 85-test mocked suite

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Ekta-9/legal-simplifier)<!-- replace with exact repo URL -->

---

## GitHub Stats

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Ekta-9&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)


</div>
