# AI Resume Analyzer

A powerful, AI-driven resume analysis application built for hackathons. It helps candidates optimize their resumes by extracting key information and comparing them against specific job descriptions.

## Features

- **PDF Text Extraction**: Seamlessly extract text from uploaded PDF resumes.
- **AI Analysis**: Powered by Google Gemini to identify:
  - Key Skills
  - Projects & Experience
  - Relevant Keywords
- **Resume Scoring**: Instant score out of 10 based on clarity, relevance, and professional language.
- **Improvement Suggestions**: Actionable advice for every section of the resume.
- **Professional Summary**: Automatically generated 2-line summary for LinkedIn or profiles.
- **Job Description Comparison**:
  - Match skills against a target JD.
  - Identify missing skills.
  - Calculate alignment percentage.

## Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS
- **AI**: Google Gemini API (@google/genai)
- **PDF Processing**: PyMuPDF (Logic implemented via pdfjs-dist for web)
- **Animations**: Motion (formerly Framer Motion)

## Installation Steps

1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set your Gemini API Key in the environment:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

## How to Run

Start the development server:
```bash
npm run dev
```
The application will be available at `http://localhost:3000`.
