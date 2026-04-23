# n8n AI Automation Portfolio

4 production-ready AI automation workflows built in n8n
using local and cloud LLMs at zero ongoing API cost.

## Workflows

### 1. Luna — RAG Customer Support Agent
AI agent that answers from your knowledge base with 
PostgreSQL memory and human escalation.
[View →](n8n_automation_portfolio/luna-rag-agent/luna-rag-agent.json)

### 2. Sentiment Feedback Router  
Analyzes customer feedback and routes personalized 
AI-generated email responses automatically.
[View →](02-sentiment-feedback-router/)

### 3. Lead Qualification Engine
Scores inbound leads 1-10 with AI, routes hot leads 
to urgent alerts and cold leads to nurture emails.
[View →]([03-lead-qualifier/](https://github.com/AbdelrahmanMwafyy/n8n-ai-automation-portfolio/blob/c53ec887bd5fe8e0ddcee2444f620c5c2a14ded5/n8n_automation_portfolio/lead-qualifer/lead-qualifier.json))

### 4. Quote Generator Pipeline
Scheduled AI content generation with Sheets logging 
and Gmail delivery.
[View →](04-quote-generator/)

## Tech Stack
n8n · Ollama (local LLM) · Groq API (free cloud LLM) ·
PostgreSQL · PGVector · Gmail · Google Sheets

## Zero API Cost
All workflows use either Ollama (local, free) or 
Groq free tier (14,400 tokens/min). No OpenAI costs.

## Import Any Workflow
1. Open your n8n instance
2. Click + → Import from file
3. Select the .json file from any workflow folder
4. Add your credentials
