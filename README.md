# AuraDent AI

### **DSOLVE 2026** · DRISHTI · College of Engineering Trivandrum (CET)

**BUILD. SOLVE. DEMONSTRATE.**

|                   |                                           |
| ----------------- | ----------------------------------------- |
| **Problem:**      | Problem 7 — Real-Time Clinical Measurement|
| **Team Name:**    | Mammootty75                               |
| **Team Members:** | Bhagya · Nehala · Krishna                 |
| **Institution:**  | LBS Institute of Technology for Women     |


| **Pitch Video:**  | https://www.instagram.com/reel/Ddcf4YeTVe2/?stkn=MWhicmNwajB4c2ViNA==          |

---

## Table of Contents

- [Problem Statement](#problem-statement)
- [Our Solution](#our-solution)
- [Key Features](#key-features)
- [Screenshots & Demo](#screenshots--demo)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage / Demo Script](#usage--demo-script)
- [Limitations & Future Scope](#limitations--future-scope)
- [Team](#team)
- [Submission Checklist](#submission-checklist)

---

> **READ THIS FIRST:** This repository is a **starting template**.

---

## Problem Statement

Develop a real-time or near-real-time voice solution that enables dental professionals to capture and record clinical measurements with minimal delay.

The solution should process spoken measurements such as pocket depth, bleeding, recession, and other periodontal findings, converting them into structured data and reflecting them in the application almost instantly. It should explore ways to combine speech recognition, rule-based processing, and AI while handling corrections, repeated measurements, and natural variations in speech.

The goal is to reduce processing latency and manual data entry, creating a fast, seamless, hands-free clinical documentation experience.

> ## Problem 7: Real-Time Clinical Measurement

> Develop a real-time or near-real-time voice solution that enables dental professionals to capture and record clinical measurements with minimal delay.

### Why this matters

Dental professionals often spend significant time manually entering periodontal measurements, which can slow down examinations and interrupt their workflow. A real-time voice-based solution allows dentists to record measurements hands-free as they speak, reducing repetitive data entry, minimizing delays and potential transcription errors, and keeping clinical records updated almost instantly. This can make examinations faster, more seamless, and less disruptive, ultimately improving efficiency for dental professionals and the documentation experience for patients.

---

## Our Solution

**AuraDent AI** is a voice-first dental assistant designed to simplify and speed up clinical documentation. It allows dentists to speak dental measurements and observations naturally, which are converted into text using Groq’s Whisper speech-recognition model. An LLM then interprets the transcript and converts it into structured dental findings such as tooth number, surface, finding type, value, and unit. These findings are stored in a database and can be used to generate patient-friendly dental reports.

The system addresses the time and effort involved in manually entering periodontal measurements during examinations. Unlike basic speech-to-text tools or chatbots, AuraDent AI combines real-time voice capture, dental-specific information extraction, structured charting, database storage, and automated reporting in one workflow. This voice-to-structured-data approach aims to reduce documentation effort while allowing dentists to review and manage the extracted findings.


---

## Key Features

- Voice-Based Dental Charting – Record dental findings naturally through speech
- Real-Time AI Transcription – Converts speech into text using Whisper.
-AI-Powered Finding Extraction – Converts spoken information into structured dental data.
-Automated Patient Reports – Generates clear, patient-friendly dental visit summaries.
---

## Screenshots & Demo

| Screenshot                                            | Description                          |
| ----------------------------------------------------- | ------------------------------------ |
|  |        
| <img width="1968" height="1322" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/a737011b-6315-4328-8bfa-c58cb495790d" />|                                               shows the ai mic which is used for active recordings |
|
| [Pitch Video](./assets/pitch/README.md)               | https://www.instagram.com/reel/Ddcf4YeTVe2/?stkn=MWhicmNwajB4c2ViNA==   |

---

## Tech Stack

| Layer           | Technology                         | Why we chose it |
| --------------- | ---------------------------------- | --------------- |
| Frontend        | web-based dental interface         |  Can display live transcription and extracted findings.|
| Backend         | python                             | Can handle the application APIs, AI processing, report generation, and email functionality in one backend.|
| Database        | SQLite                             | Good for prototype |
| ML / AI         | Whisper Large V3 Turbo             | Speech-to-text conversion|

> **Only a sample** — fill in the **"Technology"** column with your own choices.
> No language, framework, architecture, or project structure is prescribed; use
> whatever works best for your team.

---

## Getting Started

### Prerequisites

-Python 3.x — backend runtime
Node.js + npm — frontend/build runtime
React 19 + TypeScript — frontend
Vite — frontend development/build tool
SQLite — local database
Web Speech API — voice input and text-to-speech
Groq API — AI/speech processing, if using the backend AI version

The project documentation specifically identifies Vite + React 19 + TypeScript for the frontend and the Web Speech API for speech recognition/synthesis.

Groq API key — required if the backend's Groq-based AI functionality is being used.
No separate account is required for SQLite.
### Environment Variables

| Variable       | Description                       | Example                           |
| -------------- | --------------------------------- | --------------------------------- |
| `API_KEY`      | API key for a third-party service | `sk-xxxxxxxxxxxxxxxxxx`           |
| `DATABASE_URL` | Database connection string        | `your-database-connection-string` |
| `PORT`         | Port the backend listens on       | `8000`                            |

> Values above are illustrative examples — replace them with your own. Never
> commit real keys: use a `.env` file (already gitignored) or `.env.example`.

---

## Usage / Demo Script

_This doubles as your live demo runbook (3–5 min)._

Boot — Start the Python backend and React/Vite frontend.
Walkthrough step 1 — Open the AuraDent AI dental interface and select/start a patient examination. The judge sees the interactive dental chart and the live application interface.
Walkthrough step 2 — Speak a clinical finding naturally, for example:
“Tooth 36, pocket depth 6 millimeters, bleeding positive.”
The system captures the audio, sends it to Whisper for transcription, and displays the transcript.
Highlight — The “wow” moment — Show how the spoken sentence is transformed into structured dental findings such as tooth number, finding type, value, and unit, rather than simply displaying raw speech-to-text. The finding can then be stored and used for report generation.
Wrap-up — Explain that AuraDent AI connects voice → AI transcription → dental information extraction → structured charting → patient report. For production, the system can be extended with PostgreSQL, authentication, stronger validation, audit logs, and scalable cloud infrastructure.

## Limitations & Future Scope

### Known Limitations


- AI transcription/parsing can make mistakes, particularly with numbers, tooth identifiers, accents, background noise, or ambiguous speech.
-The current prototype is not yet a hospital-scale deployment; it uses a lightweight architecture and requires further work for multi-user scalability, advanced security, and production healthcare integration.
### Future Scope

- Hospital-scale deployment — Migrate from SQLite to PostgreSQL and introduce authentication, role-based access, scalable AI workers, and multi-user support.
-Improved clinical reliability — Add confidence scoring, dental-specific validation, ambiguity detection, stronger human    verification, and formal accuracy testing.
-Healthcare integration — Integrate with existing hospital/EHR or dental practice-management systems.
-Enhanced security — Add encryption, detailed audit trails, secure cloud storage, and healthcare-data compliance mechanisms.
---

## Team

| Name     | Role(s)                         | GitHub    | Email   |
| -------- | ------------------------------- | --------- | ------- |
| [Nehala] | ai voice                        | @nehala11 | [nehalafirosh@gmail.com] |
| [krishna] | backend developer              | @vscodeggg | krishnaaparnanair@gmail.com   |
| [bhagya]  | frontend developer             | @bhaggpie  | bhagyashiju@gmail.com
---

## Submission Checklist

**Before 6:00 AM (Code Freeze) – Sat, Sept 19th:**

- [ ] Clean, runnable source code committed to this **public** repo
- [ ] `README.md` fully filled in (all sections above)
- [ ] Pitch video (>30s, English) posted on team member's social profile
      tagging **@DrishtiCET** & **@CareStack** and link added above
- [ ] All secrets/API keys removed from the repo
- [ ] Quick-start verified from a fresh clone (`git clone` → run)

---

**[Problem Statements](./docs/problem-statements.md)** ·
**[Submission Checklist](./SUBMISSION_CHECKLIST.md)** ·
**DSOLVE 2026 Guidelines**
