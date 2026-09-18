# AuraDent AI

### **DSOLVE 2026** · DRISHTI · College of Engineering Trivandrum (CET)

**BUILD. SOLVE. DEMONSTRATE.**

|                   |                                           |
| ----------------- | ----------------------------------------- |
| **Problem:**      | Problem 7 — Real-Time Clinical Measurement|
| **Team Name:**    | Mammootty75                               |
| **Team Members:** | Bhagya · Nehala · Krishna                 |
| **Institution:**  | LBS Institute of Technology for Women     |
| **Live Demo:**    | [Demo link goes here]                     |
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

- **Feature 1** — [what it does]
- **Feature 2** — [what it does]
- **Feature 3** — [what it does]
- **Feature 4** — [what it does]

---

## Screenshots & Demo

| Screenshot                                            | Description                          |
| ----------------------------------------------------- | ------------------------------------ |
| [Screenshot 1](./assets/screenshots/screenshot-1.png) | [What it shows]                      |
| [Screenshot 2](./assets/screenshots/screenshot-2.png) | [What it shows]                      |
| [Pitch Video](./assets/pitch/README.md)               | Link to your >30s social pitch video |

---

## Tech Stack

| Layer           | Technology                         | Why we chose it |
| --------------- | ---------------------------------- | --------------- |
| Frontend        | [your frontend framework/platform] | [reason]        |
| Backend         | [your backend framework/platform]  | [reason]        |
| Database        | [your database]                    | [reason]        |
| ML / AI         | [your AI/ML tools/models]          | [reason]        |
| Infra / Hosting | [where your solution runs]         | [reason]        |

> **Only a sample** — fill in the **"Technology"** column with your own choices.
> No language, framework, architecture, or project structure is prescribed; use
> whatever works best for your team.

---

## Getting Started

### Prerequisites

- Your chosen runtime(s) and tools — list them here with versions: `[e.g. runtime X ≥ version]`
- [Any accounts / API keys required]

### Installation

> Explain how to run this project

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

1. **Boot** — start backend + frontend.
2. **Walkthrough step 1** — [what the judge sees].
3. **Walkthrough step 2** — [what the judge sees].
4. **Highlight** — [the "wow" moment / core differentiator].
5. **Wrap-up** — [summary + where this goes in production].

---

## Limitations & Future Scope

### Known Limitations

- [Limitation 1]
- [Limitation 2]

### Future Scope

- [Planned improvement 1]
- [Planned improvement 2]

---

## Team

| Name     | Role(s)                         | GitHub    | Email   |
| -------- | ------------------------------- | --------- | ------- |
| [Name 1] | [e.g. Full-stack / ML / Design] | [@handle] | [email] |
| [Name 2] |                                 |           |         |

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
