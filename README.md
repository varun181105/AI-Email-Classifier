# AI Email Classifier (n8n + OpenAI)

## Overview
This project automatically classifies incoming emails using AI.  
Emails are categorized into labels such as sales, support, or spam and the results are stored in Google Sheets.

## Tools Used
- n8n
- OpenAI API
- Gmail Trigger
- Google Sheets

## Workflow
Gmail Trigger → AI Email Classification → Store Label in Google Sheets

## How It Works
1. A new email is received in Gmail.
2. The Gmail trigger activates the workflow.
3. The email content is analyzed by OpenAI.
4. AI classifies the email into predefined categories.
5. The classification result is stored in Google Sheets.

## Setup
1. Import the `workflow.json` file into n8n.
2. Configure Gmail, OpenAI, and Google Sheets credentials.
3. Activate the workflow.

## Note
API keys are not included in this repository for security reasons.
