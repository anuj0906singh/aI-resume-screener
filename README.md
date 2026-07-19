# AI Resume Screener

Automated candidate filtering system built in n8n that leverages LLMs 
to score and rank resumes against specific job descriptions — 
eliminating hours of manual first-pass review.

## Problem
Manually screening every resume against a job description is slow, 
inconsistent, and hard to scale, especially with a high volume of 
applicants.

## Solution
An n8n workflow that:
- Extracts and parses incoming resume content (Text Extractor)
- Runs it through an AI model (Gemini) to evaluate fit against a 
  specific job description
- Generates a candidate quality score and an ATS compatibility score
- Produces a clear hiring recommendation
- Logs results to Google Sheets / Google Docs
- Sends a notification via Telegram Bot

## Tools & Integrations
n8n · Gemini · Google Sheets · Google Docs · Text Extractor · 
Telegram Bot · API Integration

## Outcome
Turns a slow, subjective screening process into a fast, consistent, 
data-backed first filter — saving hours of manual review time.

## Demo
[Watch workflow demo video](link-to-your-video) — shows the n8n 
execution trace and results score in action.

---
Built by Anuj Singh · [Portfolio](https://portfoliowebsite-mu-ochre.vercel.app/)
