# 🏥 Mini Healthcare Support Web App

## Overview
This project is a concept-level healthcare support web application designed for NGOs to efficiently manage patient and volunteer queries.  
It demonstrates how modern web technologies and simple AI-based automation can reduce response time and improve support operations.

The application is built using **Next.js and React**, with backend logic handled via **Next.js API routes**.

---

## Problem Statement
Healthcare NGOs often receive a high volume of support requests through emails or messaging platforms.  
Manually reading, prioritizing, and responding to each request is time-consuming and error-prone.

---

## Solution
This web app provides:
- A simple healthcare support form
- Automated analysis of user queries
- Priority classification to identify urgent cases
- AI-style summarization and response suggestions

This helps NGOs respond faster and focus on critical cases.

---

## Key Features
- Patient / Volunteer support form
- AI-based urgency detection (High / Medium / Low)
- Automated message summarization
- Suggested response generation
- Clean and user-friendly interface
- Backend logic implemented using Next.js API routes

---

## Tech Stack
- **Frontend:** Next.js (React)
- **Backend:** Next.js API Routes
- **Styling:** Global CSS
- **AI / Automation:** Rule-based NLP logic (concept-level)

---

## AI / Automation Concept
The system analyzes the submitted healthcare request using keyword-based NLP logic to:
- Detect urgency in the message
- Generate a concise summary
- Suggest an appropriate response for NGO staff

Although rule-based, this concept demonstrates how AI-driven triage can be implemented and later upgraded to real NLP or LLM models.

---

## NGO Use Case
This application can help healthcare NGOs:
- Prioritize urgent patient cases
- Reduce manual workload for volunteers
- Improve response turnaround time
- Organize incoming support requests efficiently

---

## Future Enhancements
- Database integration for persistent storage
- Integration with real NLP / LLM APIs
- Email or SMS alerts for high-priority cases
- Admin dashboard for NGO staff
- Multi-language support

---

## How to Run Locally
```bash
npm install
npm run dev
