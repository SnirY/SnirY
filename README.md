# Hi, I'm Snir 👋

Software Engineering graduate focused on Python backend development, full-stack engineering, and AI applications, with project experience in machine learning and computer vision.

**B.Sc. Software Engineering, Braude College (2026) · Israel**

## Selected Projects

### Job Intelligence Platform

My main project: a full-stack application that turns job postings into structured requirements and matches them against a candidate profile, showing per-requirement fit and skill gaps.

- **Backend & web:** FastAPI and Next.js, with PostgreSQL and SQLAlchemy.
- **Matching engine:** deterministic and versioned; links each supported match to evidence from the candidate profile and flags unmet requirements.
- **LLM integration:** resume import pipeline with schema validation, versioned prompts, and run tracking.
- **Infrastructure:** background processing with Redis/RQ, authentication, and database migrations with Alembic.
- **Testing:** automated regression tests running in CI with GitHub Actions.

**Stack:** Python, FastAPI, Next.js, PostgreSQL, SQLAlchemy, Redis/RQ, Docker, pytest, GitHub Actions

*Source code is private; a demo walkthrough is available on request.*

### [Infant Length Measurement System](https://github.com/SnirY/Infant-Length-Measurement-System)

B.Sc. final project (team of 2): a computer vision prototype for estimating infant head-to-heel length from a single top-down RGB image.

- Combines YOLOv8 reference-object detection, OpenPose keypoints, and image calibration to convert pixel measurements into centimeters.
- Provides an offline desktop interface with annotated results for visual inspection.
- Evaluated as a non-clinical feasibility prototype using an infant-sized doll.

**Stack:** Python, YOLOv8, OpenPose, OpenCV, Tkinter

### Football Match Prediction

Machine learning pipeline for predicting football match outcomes from historical data and football statistics APIs.

- Collects and stores football data in PostgreSQL.
- Trains XGBoost models on features derived from historical team form and player statistics.
- Evaluates models with chronological, season-based backtesting designed to avoid look-ahead bias.

**Stack:** Python, XGBoost, PostgreSQL, REST APIs

*Repository not yet public.*

## Technical Skills

| Area | Technologies |
|---|---|
| Languages | Python, TypeScript, JavaScript, SQL, Java, C |
| Backend & Web | FastAPI, SQLAlchemy, REST APIs, Next.js, React |
| Data & Background Processing | PostgreSQL, Redis/RQ, Alembic |
| Machine Learning & Computer Vision | XGBoost, YOLOv8, OpenPose, OpenCV |
| Development & Testing | Git, Linux, Docker, pytest, GitHub Actions |

## Background

Before my degree, I led a technical team maintaining and operating radar and detection systems in the IDF's Arrow missile defense unit, focusing on troubleshooting and operational readiness.

I'm looking for junior software engineering roles in backend, full-stack, and AI applications, and I'm also interested in machine learning and computer vision roles.

## Get in Touch

[LinkedIn](https://www.linkedin.com/in/snir-yehuda-9620a917) · [Email](mailto:snir.yeuda@gmail.com)

<!--
**SnirY/SnirY** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
