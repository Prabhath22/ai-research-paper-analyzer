# AI Research Paper Analyzer

This project is an AI workflow built with n8n that analyzes research papers.

## Features
- Upload PDF research paper
- Extract text automatically
- Generate:
  - Summary
  - Key Contributions
  - Advantages
  - Limitations
  - Future Work

## Architecture

Webhook → Extract PDF → LLM Analysis → Generate Report

## Technologies
- n8n
- Groq LLM
- PDF text extraction
- Webhook APIs

## How to Use
1. Import workflow.json into n8n
2. Start the webhook
3. Upload a research paper PDF
4. Download the generated analysis
