# AI Study Assistant

A phase-based AI-powered study assistant designed to convert raw study material into structured outputs such as summaries, bullet points, and exam-ready notes.

This project focuses on **architecture, scalability, and safe AI integration**, rather than immediate full AI deployment.

---

## Problem Statement

Students often struggle to convert large volumes of study material into concise, exam-oriented notes. Manual summarization is time-consuming and inconsistent.

This project aims to solve that problem using Generative AI — in a secure and scalable way.

---

## Project Phases

### Phase 1 – UI Prototype (Completed)
- Browser-based interface
- Text input for study material
- Buttons for:
  - Summary
  - Bullet Points
  - Exam-Ready Notes
- Logic simulated using rule-based JavaScript (no real AI)

> Phase 1 implementation exists as a separate prototype repository.

---

### Phase 2 – Architecture & Refactor (Completed)
- Clean separation of frontend and backend responsibilities
- Backend responsible for:
  - Request validation
  - Prompt formatting
  - Output standardization
- Frontend responsible only for UI and user input

No real AI API is integrated at this stage.

---

### Phase 3 – Backend API (Planned)
- Node.js / Python backend
- REST API endpoints
- Secure handling of user input
- Centralized AI call layer

---

### Phase 4 – Real Generative AI Integration (Planned)
- Integration with a real Generative AI API
- API keys stored securely on the backend
- Prompt engineering for:
  - JNTUH exam pattern
  - Structured academic output
- Rate limiting and cost control

---

## Why Not Call AI Directly From the Browser?

Calling Generative AI APIs directly from the browser is discouraged due to:
- API key exposure
- Uncontrolled usage and cost
- Risk of prompt injection
- Intellectual property leakage

This project follows **industry best practices** by placing AI calls strictly on the backend.

---

## Tech Stack (Planned)

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js / Python
- AI: Generative AI APIs (future phase)

---

## Project Status

- Phase 1: ✅ Completed
- Phase 2: ✅ Completed
- Phase 3: ⏳ Planned
- Phase 4: ⏳ Planned

---

## Note

This repository currently documents **architecture and design decisions**.  
Implementation will be added incrementally in future phases.
