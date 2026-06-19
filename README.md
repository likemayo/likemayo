# **Yanlin Wu — GitHub Portfolio**

Welcome! I'm **Yanlin Wu**, a Computer Science & Economics student at NYU Abu Dhabi specializing in **AI-driven systems**, **full-stack development**, and **data-powered product design**. My work spans production-style software engineering, machine learning, educational technology, and accessibility-focused projects.

This profile highlights selected projects that show both technical depth and practical product thinking — from backend infrastructure and adaptive learning systems to ML competitions and social impact tools.

---

# 🌟 Featured Projects

## 1. E-Commerce Platform with Partner Catalog Ingest & RMA System

Repository: [E-Commerce Platform (Full-Stack, Dockerized)](https://github.com/likemayo/Checkpoint4)

Summary: A production-oriented, Dockerized Flask e-commerce backend combining a durable partner catalog ingestion pipeline (CSV/JSON adapters), an async background worker for ingest and business logic, and a full return merchandise authorization (RMA) workflow.

This project introduces several production-oriented improvements that strengthen the platform's backend reliability, operational visibility, and user experience. The additions focus on designing scalable workflows for catalog ingestion, flash sales, and returns management.

Key upgrades include **server-side data filtering**, **operational alerting**, and a **durable notification pipeline** integrated directly into the platform's RMA workflow. These additions required careful coordination between API design, asynchronous processing, and persistence.

On the system-level side, the checkpoint adds comprehensive **observability hooks**, including structured JSON logging with correlation IDs, Prometheus metrics for both HTTP and business events, and operational dashboards for monitoring system health.

Overall, this project transforms the platform from a feature-complete prototype into a more **production-ready backend**, emphasizing clean API design, operational robustness, and software engineering best practices.

Highlights
- Partner catalog ingestion via CSV/JSON adapters, async job queue, audit logging
- Flash sales engine: real-time inventory tracking, rate limiting, circuit breaker
- End-to-end RMA system: validation → inspection → disposition → refund/repair/replacement
- Mobile-friendly customer dashboard + multi-queue admin portal
- Fully containerized: `docker-compose up` to run app + worker
- Comprehensive test suite (unit, integration, stress tests)

Tech Stack: Flask, SQLite, Docker, Async Worker, Prometheus-style metrics, pytest
Best for: SWE, Platform, Backend, Product Infra roles

---

## 2. EduCode — Adaptive Learning Platform for Programming

Repository: educode-adaptive-platform (Capstone) - https://github.com/Sophie-l-l/capstone

A full-stack **adaptive coding education platform** that uses **Bayesian Knowledge Tracing (BKT)** to track student mastery and recommend personalized next steps. The system evaluates submissions across both **technical correctness** and **cognitive understanding**, combining **rule-based error detection** with the **Google Gemini API** for more complex cases.

Highlights
- Next.js frontend, Express/Prisma backend, and FastAPI AI service
- Judge0 integration for secure code execution and automated scoring
- Multi-layer feedback for technical errors, cognitive gaps, and learning-level classification
- Hybrid error analysis using **rule-based logic + Gemini API**
- BKT-based mastery tracking across multiple Knowledge Components
- Instructor dashboard for student progress and analytics
- Dockerized dev/prod setup with nginx reverse proxy

Tech Stack: Next.js, Node.js/Express, Python FastAPI, PostgreSQL, Docker, Judge0, Prisma
Best for: EdTech, Full-Stack SWE, AI/ML Engineering, Product roles

---

# 🤖 Machine Learning & Data Projects

## 1. Jane Street Market Prediction (Kaggle — Silver Medal Top 4%)

Repository: Kaggle-JaneStreetCompetition — https://github.com/likemayo/Kaggle-JaneStreetCommpetition

Real-time financial prediction using advanced ML models.

Highlights
- Analyzed **47M+** financial samples across 1,699 trading days
- Feature engineered lagged, smoothed, and aggregated signals
- Built LightGBM, XGBoost, CatBoost + PyTorch Lightning neural networks
- Reduced prediction error significantly (0.0083) with tuned ensemble
- Top 4% globally on Kaggle leaderboard

Tech Stack: Pandas, NumPy, LightGBM, XGBoost, CatBoost, PyTorch Lightning

---

# ✋ AI for Accessibility & Social Impact

## ChatSign — Sign Language Translation & Recognition

Repository: youtube_scraping — https://github.com/likemayo/youtube_scraping

A sign language data collection and preprocessing project for improved accessibility tools.

Highlights
- Scraped and processed 2,000+ labeled clips from YouTube
- Managed multimodal preprocessing for ASL/LIBRAS datasets
- Integrated into broader sign-language translation research
- Conducted user research with 40+ deaf/hard-of-hearing participants

---

# 🛠️ Technical Skills

Programming
Python • JavaScript/TypeScript • C/C++ • SQL • Java

Frameworks & Tools
Flask • FastAPI • Express • Next.js • React • Tailwind • Prisma
PyTorch • TensorFlow • Scikit-learn • Pandas • NumPy
Docker • SQLite • PostgreSQL
Judge0 • Prometheus-style metrics

Core Strengths
- Full-stack engineering
- ML modeling & analytics
- Data pipeline design
- API design & backend infrastructure
- Product thinking (user flows, validation, iterative design)

---

# 📫 Contact Me

Email: yw6739@nyu.edu
Portfolio Website: https://likemayo.github.io
LinkedIn / Resume available upon request

---
