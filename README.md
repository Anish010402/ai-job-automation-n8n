# 🚀 AI Job Automation System (n8n + LLM)

## 📌 Overview
This project automates job discovery, resume scoring, and resume generation using AI workflows.

## ⚙️ Features
- Scrapes jobs using Apify
- Uses LLMs to analyze job descriptions
- Scores resume-job fit
- Filters relevant roles
- Generates tailored resumes
- Converts JSON → LaTeX → PDF
- Stores everything in Google Sheets + Drive

## 🧠 Tech Stack
- n8n
- Apify
- OpenAI / Gemini / Groq
- Google Sheets API
- LaTeX
- Docker

## 📂 Setup Instructions

1. Import `workflow.json` into n8n
2. Add credentials:
   - Apify
   - LLM API
   - Google Sheets
   - Google Drive
3. Update IDs:
   - Sheet ID
   - Folder ID
4. Run the workflow

## 📸 Screenshots
(Add your images here)

## 💡 Impact
- Reduced manual effort by 80–90%
- Made job applications more targeted

## 🚧 Future Work
- Auto-apply system
- Application tracking
