# Motivational Quote Generator

Generates AI quotes and sends via email on schedule.

## Flow
Trigger → Ollama generates quote → 
Google Sheets log → Gmail sends

## Tech Stack
n8n · Ollama · Google Sheets · Gmail

## Import
1. Open n8n → Import from file
2. Select quote-generator.json
3. Add Gmail and Google Sheets credentials