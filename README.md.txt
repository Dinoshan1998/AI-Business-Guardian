# 🚀 AI Business Guardian

### AI-Powered Business Intelligence & Risk Detection Automation

AI Business Guardian is an intelligent business automation project built using n8n and Google Gemini AI. It analyses customer feedback, detects potential lost-sales risks and generates actionable business insights.

## ✨ Key Features

- Customer feedback collection through Google Forms
- AI-powered sentiment and intent analysis
- Customer urgency and risk-score assessment
- Potential lost-sales opportunity detection
- Automated data storage using Google Sheets
- High-risk customer alerts through Telegram
- Human-in-the-loop approval
- Gmail response draft generation

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Google Gemini AI | AI-powered analysis |
| Google Forms | Customer feedback collection |
| Google Sheets | Data storage |
| Telegram | Human approval and alerts |
| Gmail | Email draft generation |

## 🔄 Workflow Architecture

Google Forms → Google Sheets Trigger → Gemini AI Analysis → Risk Detection → Telegram Approval → Gmail Draft

Low-risk feedback follows a separate workflow branch.

## 📂 Project Structure

- `workflows/` – Exported n8n workflow
- `screenshots/` – Workflow and execution screenshots
- `docs/` – Project documentation

## 🚀 Setup

1. Install and configure n8n.
2. Import the workflow JSON into n8n.
3. Configure Google Sheets credentials.
4. Configure Google Gemini API credentials.
5. Configure Telegram Bot credentials.
6. Configure Gmail OAuth2 credentials.
7. Update the required spreadsheet and workflow settings.
8. Test the workflow with sample customer feedback.

## 🔐 Security

Credentials and API keys are not included in this repository. Configure your own credentials inside n8n.

## 🎯 Project Objective

Demonstrate how AI agents and workflow automation can help businesses understand customer feedback, identify potential risks and support better business decisions.

**Developed as an AI Engineering Portfolio Project.**