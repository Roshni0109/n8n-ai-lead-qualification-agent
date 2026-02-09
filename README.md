# n8n-ai-lead-qualification-agent
AI-powered lead qualification and routing automation built with n8n


# AI Lead Qualification Agent (n8n)

## Overview
This project is an AI-powered lead qualification workflow built using n8n.
It automatically evaluates inbound leads, classifies them by business type,
and routes them appropriately using AI-driven decision-making.

## How It Works
1. Lead submits a form with name, email, company website, and request
2. Workflow researches the company website via HTTP API
3. AI Agent analyzes:
   - Business model
   - Industry fit
   - Intent
4. Lead is classified as:
   - SaaS
   - Development Agency
5. Automated email response is triggered:
   - Qualified leads → Sales notification
   - Unqualified leads → Polite rejection email

## Business Use Case
Designed for recruitment firms and service businesses that:
- Receive high inbound lead volume
- Want faster response times
- Need to focus sales efforts on high-quality prospects

## Tech Stack
- n8n
- Google Gemini (AI)
- HTTP APIs
- Gmail Automation

## How to Import
1. Open n8n
2. Click "Import workflow"
3. Upload `Lead Qualification Agent.json`
4. Configure credentials (Gmail, AI API)

## Author
Roshni Multani
