# Luna — RAG Customer Support Agent

AI support agent that answers from your knowledge base,
remembers conversations, and escalates to humans.

## What It Does
- RAG: answers only from uploaded knowledge base
- PostgreSQL conversation memory (persists across sessions)
- PGVector semantic search
- Human escalation when confidence is low
- Appointment booking tool
- Zero API cost using Ollama local LLM

## Tech Stack
n8n · Ollama · PostgreSQL · PGVector · Gmail

## Import This Workflow
1. Open n8n
2. Click the + button → Import from file
3. Select luna-rag-agent.json
4. Add your Ollama and PostgreSQL credentials

## Business Value
Handles 80% of customer queries automatically.
Escalates edge cases to your team instantly.
No hallucination — only answers from your actual data.