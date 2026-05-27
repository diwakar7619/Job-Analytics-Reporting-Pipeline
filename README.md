# Automated Hiring Trend Analyzer

An automated job market intelligence pipeline built using n8n, OpenRouter, and Google Sheets.

The workflow scrapes job listings from platforms like Internshala, extracts structured job data using LLM-powered information extraction, analyzes hiring trends, and automatically sends summarized market intelligence reports via email.

---

## Features

- Automated scheduled scraping
- Structured job data extraction
- Skill normalization
- Hiring trend analysis
- Google Sheets integration
- Automated email reports
- AI-powered summarization
- Daily market insights

---

## Workflow Overview

1. Fetch job listings from job platforms
2. Extract structured fields using LLMs
3. Store extracted jobs in Google Sheets
4. Analyze hiring patterns and skill trends
5. Send summarized market analysis reports via email

---

## Tech Stack

- n8n
- OpenRouter
- OpenAI OSS Models
- Google Sheets API
- Gmail API
- JSON Schema Extraction

---

## Extracted Fields

- Job Title
- Company
- Location
- Employment Type
- Experience Level
- Skills
- Category
- Remote/Onsite Status

---

## Example Insights Generated

- Most demanded technologies
- Remote hiring trends
- Beginner-friendly opportunities
- Top hiring domains
- Regional hiring patterns
- Skill demand analysis

---

## Automation Flow

Schedule Trigger → Web Scraping → Information Extraction → Data Storage → Trend Analysis → Email Reporting

---

## Future Improvements

- PostgreSQL integration
- Multi-platform scraping
- Historical trend tracking
- Dashboard visualization
- Telegram/Discord alerts
- Skill demand forecasting

---

## Author

Pratham Diwakar
