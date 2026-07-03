# 📄 Product Requirements Document (PRD)

# CareerLens AI

**Version:** 1.0

**Project Type:** AI Resume Intelligence Platform

**Project Owner:** Anushka Das

**Start Date:** 3 July 2026

**Status:** Planning

---

# 🎯 Product Vision

CareerLens AI is an AI-powered resume intelligence platform that helps students, fresh graduates, and job seekers evaluate their resumes, understand their strengths and weaknesses, identify missing skills, estimate suitable career paths, and receive personalized improvement recommendations.

This project will evolve throughout my AI Engineer Journey into a complete AI-powered career assistant.

---

# ❗ Problem Statement

Many students and early-career professionals struggle to answer questions like:

- Is my resume ATS-friendly?
- What job roles am I best suited for?
- What skills am I missing?
- Why am I getting rejected?
- What projects or certifications should I complete?
- How can I improve my chances of getting shortlisted?

Current resume checkers either provide generic feedback or require paid subscriptions.

CareerLens AI aims to provide intelligent, actionable, and personalized career insights using Artificial Intelligence.

---

# 👥 Target Users

## Primary Users

- College Students
- Fresh Graduates
- Internship Applicants
- Entry-Level Job Seekers

---

## Secondary Users

- Career Switchers
- Bootcamp Students
- Resume Reviewers
- Placement Cells

---

# 💡 Value Proposition

CareerLens AI will allow users to upload a resume and instantly receive:

- ATS Compatibility Score
- Resume Summary
- Detected Skills
- Missing Skills
- Suggested Job Roles
- Resume Strengths
- Resume Weaknesses
- Personalized Improvement Suggestions
- Recommended Projects
- Recommended Certifications
- Future Career Roadmap

---

# 🚀 Version Roadmap

## Version 1 (Current)

### Goal

Build a strong Machine Learning + NLP foundation.

### Features

- Upload Resume PDF
- Extract Resume Text
- Clean Resume Text
- Detect Technical Skills
- Predict Suitable Job Role
- Calculate Basic ATS Score
- Show Missing Skills
- Recommend Improvements
- Interactive Streamlit Dashboard

---

## Version 2

### Goal

Improve NLP capabilities.

### Features

- Resume Section Detection
- Better Skill Extraction
- Keyword Matching
- Resume Quality Analysis
- Resume Report Generation

---

## Version 3

### Goal

Integrate Large Language Models.

### Features

- AI Resume Feedback
- AI Resume Summary
- Personalized Career Advice
- Project Recommendations
- Certification Recommendations
- Interview Question Suggestions

---

## Version 4

### Goal

Build an AI Career Assistant.

### Features

- Resume Chatbot
- Job Description Matching
- Resume Improvement Agent
- Career Planning Assistant
- Learning Roadmap Generator

---

# 🚫 Out of Scope (Version 1)

The following features will NOT be included in Version 1:

- User Authentication
- Database Storage
- Resume Builder
- Resume Templates
- Job Scraping
- Live Job Recommendations
- Multi-user Support
- LLM-based Chatbot
- AI Agents
- Cloud Database

These will be implemented in future versions.

---

# 🔄 User Flow

```text
User uploads resume

        ↓

Resume text extraction

        ↓

Text preprocessing

        ↓

Skill extraction

        ↓

Machine Learning prediction

        ↓

ATS score calculation

        ↓

Missing skills analysis

        ↓

Recommendation engine

        ↓

Interactive dashboard
```

---

# 🏗 System Architecture

```text
Resume PDF

        │

        ▼

PDF Parser

        │

        ▼

Text Preprocessing

        │

        ▼

Feature Engineering

        │

        ▼

Machine Learning Model

        │

        ▼

Prediction Engine

        │

        ▼

Recommendation Engine

        │

        ▼

Streamlit Dashboard
```

---

# 🧠 Machine Learning Pipeline

```text
Raw Resume

↓

PDF Parsing

↓

Text Cleaning

↓

Tokenization

↓

Feature Extraction (TF-IDF)

↓

Model Training

↓

Evaluation

↓

Prediction

↓

Dashboard
```

---

# 🛠 Technical Stack

## Programming

- Python

---

## Data Processing

- pandas
- NumPy

---

## Machine Learning

- scikit-learn

---

## Natural Language Processing

- NLTK
- spaCy

---

## Feature Engineering

- TF-IDF
- Count Vectorizer

---

## PDF Processing

- PyMuPDF
- pdfplumber

---

## Visualization

- Plotly
- Matplotlib

---

## Frontend

- Streamlit

---

## Deployment

- Streamlit Community Cloud

---

## Future Technologies

- Hugging Face Transformers
- LangChain
- LangGraph
- ChromaDB
- FAISS
- FastAPI
- Docker
- MLflow

---

# 📂 Planned Folder Structure

```text
AI-Resume-Intelligence-Platform

│

├── app/

├── assets/

├── configs/

├── datasets/

│   ├── raw/

│   └── processed/

├── docs/

├── models/

├── notebooks/

├── reports/

├── src/

│   ├── data/

│   ├── features/

│   ├── models/

│   ├── pipeline/

│   ├── utils/

│   ├── preprocess.py

│   ├── train.py

│   └── predict.py

├── tests/

├── requirements.txt

├── pyproject.toml

├── README.md

└── CHANGELOG.md
```

---

# 📈 Success Metrics

Version 1 will be considered successful if:

- Resume upload works correctly
- PDF text extraction succeeds
- Skill extraction identifies relevant skills
- Job role prediction achieves useful accuracy
- ATS score is generated
- Dashboard is interactive
- Project is deployed publicly
- Documentation is complete
- GitHub repository follows professional standards

---

# ⚠ Risks & Limitations

- Resume formats vary significantly.
- Some resumes may contain images instead of selectable text.
- Skill extraction may miss uncommon technologies.
- ATS score is an approximation, not an official ATS score.
- Predictions depend heavily on dataset quality.
- Performance will improve in future versions.

---

# 🏆 Engineering Principles

CareerLens AI will follow these principles throughout development.

- Build incrementally.
- Keep code modular.
- Separate experimentation from production code.
- Write clean, maintainable code.
- Document every important decision.
- Focus on solving real problems.
- Build products, not just models.
- Prioritize quality over quantity.

---

# 🔮 Long-Term Vision

By the end of the AI Engineer Journey, CareerLens AI will evolve into a complete AI-powered Career Intelligence Platform capable of:

- Resume Analysis
- Resume Chat
- AI Career Coaching
- Job Description Matching
- Learning Roadmap Generation
- Personalized Interview Preparation
- AI Project Recommendations
- Certification Recommendations
- AI-powered Career Guidance

---

> **Mission Statement**

> *Empowering every student and job seeker with intelligent, personalized, and accessible AI-driven career guidance.*