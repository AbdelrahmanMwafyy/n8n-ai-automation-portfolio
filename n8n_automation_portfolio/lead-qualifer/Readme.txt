# AI Lead Qualification Engine

Scores inbound leads 1-10 automatically and routes
hot leads to urgent alerts, cold leads to nurture emails.

## Flow
Form submission → Groq AI scores lead (HOT/WARM/COLD) →
Hot leads: urgent Gmail alert + Sheets log →
Cold leads: nurture email + Sheets log →
Auto-reply to lead with personalized message

## Tech Stack
n8n · Groq API (free) · Gmail · Google Sheets

## Import
1. Open n8n → Import from file
2. Select lead-qualifier.json
3. Add Groq API key (free at console.groq.com)
4. Add Gmail and Google Sheets credentials

## Business Value
Qualifies every lead in under 30 seconds.
Sales team only sees pre-scored hot leads.