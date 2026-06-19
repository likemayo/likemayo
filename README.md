# **Vanessa Wu — GitHub Portfolio**

Welcome! I'm **Yanlin Wu**, a Computer Science & Economics student at NYU Abu Dhabi specializing in **AI-driven systems**, **full-stack development,** and **data-powered product design**. My work spans production-ready engineering, machine learning, developer tooling, and adaptive learning systems.

Below is a curated selection of my most significant projects, organized for quick review by recruiters and engineering leads.

---

# 🌟 Featured Projects

## 1. E-Commerce Platform with Partner Catalog Ingest & RMA System

Repository: E-Commerce Platform (Full-Stack, Dockerized)

This project introduces several production-oriented improvements that strengthen the platform’s backend reliability, operational visibility, and user experience. The additions focus on designing secure APIs, implementing event-driven workflows, and improving system observability across the stack.

Key upgrades include **server-side data filtering**, **operational alerting**, and a **durable notification pipeline** integrated directly into the platform’s RMA workflow. These additions required building parameterized SQL queries, designing configurable backend logic, and ensuring efficient database access patterns through index-friendly queries and environment-driven configuration.

On the system-level side, the checkpoint adds comprehensive **observability hooks**, including structured JSON logging with correlation IDs, Prometheus metrics for both HTTP and business events, and detailed health-check endpoints. Together, these tools improve traceability, debugging, and performance analysis in a containerized environment, making the system easier to operate and scale.

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

A multi-service **adaptive coding education platform** using **Bayesian Knowledge Tracing (BKT)** to model student mastery and generate personalized recommendations.

Highlights
- Classroom-ready platform with Next.js frontend, Express/Prisma backend, and FastAPI AI service
- Integrated Judge0 for code execution and automated scoring
- Tracks Knowledge Components (KCs) and updates skill mastery via BKT
- Instructor analytics dashboard for student progress
- Face/Emotion data pipeline scaffolded for future adaptive feedback
- Full Docker dev/prod environment with nginx reverse proxy

Tech Stack: Next.js, Node.js/Express, Python FastAPI, PostgreSQL, Docker, Judge0, Prisma
Best for: EdTech, AI/ML Engineering, Full-Stack SWE, Product roles

---

## 3. Mobile-Friendly Calorie Tracking & Weight Loss App

Repository: calories — https://github.com/likemayo/calories

A lightweight, mobile-optimized web app to support calorie deficit goals with practical portion-based estimations.

Highlights
- Personalized daily calorie targets using Mifflin-St Jeor equation
- Fast meal logging with multi-item entries and intuitive portion units
- Food calorie estimator with approximate matching + built-in food DB
- Access from any phone on same WiFi or via ngrok/cloud deployment
- Clean UI with bottom navigation for one-handed use

Tech Stack: Python, Flask
Best for: Mobile Web, Consumer App, Health Tech, UX-oriented projects

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

Tech Stack: Pandas, NumPy, LightGBM, XGBoost, CatBoost, PyTorch Lightning

---

## 2. End-to-End ML Model Development

Repository: ML_Model — https://github.com/likemayo/ML_Model

A showcase of ML workflows: preprocessing → model training → evaluation.

Highlights
- Implemented classical supervised learning models
- Strong emphasis on reproducibility and experimentation
- Covers regression, classification, and model diagnostics

---

## 3. Text Sentiment Analysis (Logistic Regression)

Repository: EmotionalAnalysisText — https://github.com/likemayo/AI_Project/blob/main/EmotionalAnalysisText/EmotionDetection.py

Highlights
- Trained on Sentiment140 dataset (1.6M tweets)
- Built complete NLP pipeline: tokenization, cleaning, feature extraction
- Deployed logistic regression sentiment classifier

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

# 🌐 Personal Website

Repository: likemayo.github.io — https://likemayo.github.io
A simple static site hosting my portfolio and project showcases. Built with HTML/CSS/JS, deployed on GitHub Pages.

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
