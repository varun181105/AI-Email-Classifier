# AI Report Generator Automation (n8n + OpenAI)

## Overview
This project is an AI-powered report generation automation built using n8n and OpenAI.  
It receives input data via webhook, generates a structured report using AI, creates a Google Docs file, and sends the report via email.

## Tools Used
- n8n
- OpenAI API
- Webhook Trigger
- Google Docs
- Gmail

## Workflow
Webhook → Edit Fields → AI Report Generation → Create Google Doc → Update Document → Send Email

## How It Works
1. Data is sent to the webhook.
2. The workflow processes and structures the input.
3. OpenAI generates a detailed report.
4. A new Google Doc is created.
5. The report content is added to the document.
6. The final report is sent via email.

## Setup
1. Import the `workflow.json` file into n8n.
2. Configure OpenAI, Google Docs, and Gmail credentials.
3. Activate the workflow.

## Note
API keys are not included in this repository for security reasons.
