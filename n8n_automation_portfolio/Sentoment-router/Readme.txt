# AI Sentiment Feedback Router

Automatically analyzes customer feedback sentiment and 
routes to personalized AI-generated email responses.

## Flow
Form submission → AI sentiment analysis → 
Branch (Positive/Negative) → 
AI generates personalized email → Gmail sends → 
Google Sheets log

## Tech Stack
n8n · Ollama · Gmail · Google Sheets

## Import
1. Open n8n → Import from file
2. Select sentiment-feedback-router.json
3. Add Gmail and Google Sheets credentials

## Business Value
Eliminates manual review of customer feedback.
Every customer gets a personalized response instantly.