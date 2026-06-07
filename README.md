# Gmail AI Automated Reply Agent

## Project Overview

Gmail AI Automated Reply Agent is a production-style email automation workflow built using n8n and Cohere AI.

The system automatically fetches the latest unread emails, analyzes their content using AI, generates professional context-aware replies, sends responses within the original email thread, and stores all processed email data in Google Sheets for future analysis and dataset creation.

The workflow is designed to handle multiple emails in a single execution and can process up to 10 recent unread emails automatically.

---

## Features

* Automatic Gmail inbox monitoring
* Fetches up to 10 recent unread emails
* AI-powered email summarization
* Email categorization and priority detection
* Context-aware professional reply generation
* Automatic Gmail thread replies
* Google Sheets data logging
* Structured JSON output parsing
* Batch email processing
* Dataset creation for future AI training and analytics

---

## Workflow Architecture

Schedule Trigger
→ Fetch Recent Unread Emails (Max 10)
→ Email Content Extraction
→ AI Email Analysis (Cohere)
→ Categorization & Priority Detection
→ Structured Output Parser
→ AI Reply Generation
→ Gmail Thread Reply
→ Google Sheets Logging

---

## Technologies Used

* n8n
* Gmail API
* Google Sheets API
* Cohere API
* JSON Structured Output
* AI Agents
* Workflow Automation

---

## AI Capabilities

### Email Analysis Agent

The first AI agent:

* Summarizes email content
* Categorizes emails
* Detects priority level
* Identifies action requirements
* Extracts actionable tasks

### Reply Generation Agent

The second AI agent:

* Generates professional email responses
* Adapts tone according to email category
* Handles recruitment, support, finance, work, and personal communications
* Produces thread-aware business responses

---

## Data Collection

Every processed email is stored in Google Sheets including:

* Sender Name
* Sender Email
* Subject
* Email Summary
* Category
* Priority
* Action Required
* Generated Reply
* Timestamp

This creates a structured dataset that can be used for:

* AI fine-tuning
* Email analytics
* Business intelligence
* Customer support insights

---

## Installation

1. Clone the repository.
2. Import the workflow JSON into n8n.
3. Configure Gmail credentials.
4. Configure Google Sheets credentials.
5. Configure Cohere API credentials.
6. Activate the workflow.
7. Execute the workflow.

---

## Future Enhancements

* Sentiment Analysis
* Multi-language Email Support
* Slack Notifications
* CRM Integration
* Email Intent Detection
* Auto Follow-up Generation
* RAG-based Email Knowledge Base
* Human Approval Workflow
* Dashboard & Analytics

---

## Repository Structure

workflow/
├── gmail-ai-auto-reply.json

images/
├── workflow-overview.png
├── gmail-trigger.png
├── ai-analysis.png
├── reply-generation.png
└── sheet-output.png

README.md

---

## Author

Deepak Takshak

AI Engineer | Automation Developer

GitHub: https://github.com/deepak050805

---

## Project Goal

Build a scalable AI-powered email automation system capable of processing multiple emails simultaneously, generating professional responses, and creating high-quality datasets for future AI-driven communication systems.
