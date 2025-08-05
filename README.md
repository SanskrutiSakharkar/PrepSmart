# PrepSmart – AI-Powered Interview Feedback Platform

PrepSmart is a full-stack web application designed to help job seekers receive intelligent feedback on their interview responses and resume alignment. It leverages voice input, natural language processing (NLP), and resume-job matching to provide structured insights.

## Features

- Voice-based interview response recording
- Transcription using Web Speech API
- NLP tone and keyword analysis using spaCy
- Resume and job description matching
- Progress dashboards and performance summaries

## Tech Stack

- Frontend: React.js
- Backend: Node.js (Express), Python (Flask)
- Database: MongoDB
- NLP: spaCy
- Deployment: Vercel (frontend), Render (backend)

## Folder Structure

/client # React frontend
/server # Node.js backend
/nlp-flask # Python Flask service for NLP analysis


## How to Run Locally

1. Clone the repository and navigate into each folder.
2. Install dependencies:
   - `npm install` (for frontend and backend)
   - `pip install -r requirements.txt` (for Flask service)
3. Set up MongoDB and environment variables.
4. Run services:
   - Frontend: `npm start`
   - Backend: `node index.js`
   - Flask NLP: `python app.py`

## Status

This project is in active development as part of a postgraduate capstone at the University of Waikato.
