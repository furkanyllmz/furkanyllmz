# Hi, I'm Furkan 👋

Computer Engineering student at **Ankara University** and part of the three-person team behind **[MoganAI](https://github.com/moganai)**, a family of Turkish foundation models trained from scratch. I work across the full stack of ML: data pipelines, tokenizers, pretraining, fine-tuning, and shipping models inside real products.

- 🔭 Currently building Turkish encoders and retrieval models at MoganAI
- 🧠 Interested in low-resource / agglutinative language modeling, retrieval, and domain-specific LLMs
- 🛠️ Comfortable going from raw data → trained model → deployed app (web & iOS)
- 📫 Reach me at **furkanyl509@gmail.com**

---

## 🇹🇷 MoganAI — Turkish Foundation Model Family (2025–2026)

- Built a **200B-token pretraining corpus** from ~10 TB of raw Turkish web, legal, academic, and official documents with multi-stage cleaning, deduplication, and quality filtering
- Trained a custom **SentencePiece tokenizer** designed around Turkish's agglutinative morphology
- Trained **MoganBERT-TR**, a ~149M-parameter ModernBERT-based encoder from scratch using a **CLM → MLM biphasic curriculum**, which delivered **2.7–6.9× gains** on retrieval metrics over a pure-MLM baseline in 10B-token ablations
- Ran all training on self-funded, rented **4×H100** with no institutional backing, and more than doubled GPU utilization through pipeline optimizations
- Fine-tuned the base encoder into two downstream models:
  - **MoganBERT-embed**: single-vector embedding model (distillation + contrastive training, evaluated on MTEB-TR)
  - **MoganColBERT-TR**: 148.9M-parameter late-interaction multi-vector retrieval model (token-level MaxSim)

## 📄 Publications

- **MoganBERT-TR: A Turkish Encoder Foundation Model Trained from Scratch with a CLM-to-MLM Curriculum**
  [arXiv:2608.25768](https://arxiv.org/abs/2608.25768)
- **MoganColBERT-TR: A Late-Interaction Multi-Vector Retrieval Model for Turkish**
  [arXiv:2608.26344](https://arxiv.org/abs/2608.26344)

---

## 💼 Experience

| Role | Company | Period |
|---|---|---|
| Software Development Intern | Doğuş Teknoloji | Sep 2025 – Oct 2025 |
| Big Data & AI Intern | HAVELSAN | Jul 2025 – Aug 2025 |
| Student Developer, IT Department | Ankara University, Faculty of Engineering | Jan 2024 – Apr 2025 |
| Board Member | AI & Image Processing Society | Mar 2023 – Jul 2024 |

- **Doğuş Teknoloji:** Spring Boot (Kotlin) + PostgreSQL REST API; React + Vite + Tailwind frontend; deployed backend via systemd on Linux and frontend on Vercel
- **HAVELSAN:** Audio classification with CNNs using MFCC / mel-spectrogram features, transfer learning, and augmentation; React + FastAPI + MongoDB app
- **Ankara University:** Maintained and modernized the faculty website; built software that automates exam and course scheduling
- **AI & Image Processing Society:** Taught Python to 250+ students, organized technical trips and conferences, launched [yazgit.com](https://yazgit.com)

---

## 🧰 Tech Stack

**ML / NLP:** Python · Hugging Face · SentencePiece · ModernBERT · ColBERT · LoRA · CatBoost · LightGBM
**Backend:** FastAPI · Spring Boot (Kotlin) · ASP.NET Core · PostgreSQL · MongoDB · Vector DBs · Nginx
**Frontend & Mobile:** React · Vite · Tailwind · Swift / SwiftUI · Firebase
**Cloud & Ops:** Linux · systemd · Vercel · Google Cloud Vision

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_LINKEDIN)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/YOUR_HF_USERNAME)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:furkanyl509@gmail.com)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true)
