# CRM Summary Automation using n8n, OpenAI & Telegram

This project is a real-world automation solution built with **n8n** that connects **Google Sheets (CRM data)** → **GPT (OpenAI)** → **Telegram**, delivering a weekly business summary in human-readable format.

## 🔧 Features

- Reads client CRM data from Google Sheets
- Uses GPT to generate weekly summary insights
- Sends the summary to Telegram via bot
- End-to-end workflow using no-code + OpenAI
- Easily reusable for any CRM or business data

## 📷 Workflow Preview

| Google Sheets CRM | n8n Workflow | Telegram Output |
|-------------------|--------------|-----------------|
| ![](screenshots/01-sheet-preview.png) | ![](screenshots/02-n8n-workflow.png) | ![](screenshots/03-telegram-output.png) |

## ⚙️ Technologies Used

- [n8n](https://n8n.io)
- Google Sheets API
- OpenAI (GPT-3.5 Turbo)
- Telegram Bot API

## 🚀 Setup Instructions

1. Clone the repo:
   ```bash
   git remote add origin https://github.com/ameenkhan8k/crm-automation-gpt-summary-n8n.git
