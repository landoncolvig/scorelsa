# ScoreLSA — AI-Powered LSA Lead Scoring SaaS

## Overview
ScoreLSA is a SaaS product that uses AI to score Google Local Services Ads (LSA) leads and recommend dispositions. It analyzes call recordings, transcripts, messages, and emails to determine lead quality, then provides clear recommendations (BOOK/FOLLOW UP/DECLINE) for the customer to action.

## Brand
- **Name**: ScoreLSA
- **Domain**: scorelsa.com
- **Tagline**: "Score Every Lead. Book More Jobs."
- **Parent Company**: Dayta Analytics LLC
- **Colors**: Navy (#0f172a), Amber (#f59e0b), Green/Blue/Red for statuses
- **Font**: Inter

## Pricing
- $600/month for up to 3,000 leads
- $20 per 100 additional leads
- 14-day free trial, no credit card required

## Tech Stack
- **Landing Page**: Static HTML, GitHub Pages
- **Backend**: Python, Cloud Run (GCP)
- **Database**: Cloud SQL (PostgreSQL) for tenant metadata, BigQuery for lead data
- **AI**: OpenAI GPT-4o Mini for scoring, Whisper for transcription
- **Payments**: Stripe
- **Auth**: Firebase Auth + Google Ads OAuth

## Project Structure
```
/index.html          — Landing page (GitHub Pages root)
/dashboard/          — Prototype dashboard
/privacy.html        — Privacy policy
/terms.html          — Terms of service
/CNAME               — Custom domain for GitHub Pages
```

## Origin
Built from production-proven lead scoring pipelines battle-tested on thousands of real LSA leads.
