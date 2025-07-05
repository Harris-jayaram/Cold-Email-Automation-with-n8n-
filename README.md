This repository contains a complete workflow setup using n8n for automating cold email campaigns. It integrates with Google Sheets (for lead management), Email nodes (for personalized outreach), and Cron triggers to send emails at scheduled times.

💡 Features:
📅 Daily email sending via Cron (e.g., 10 AM & 8 PM)

📬 Dynamic email content using Google Sheets (Subject & Body per lead)

🧠 Personalized placeholders (e.g., {{name}}) replaced automatically

✉️ Sends emails using SMTP (Gmail, Outlook, etc.)

📊 Easy lead tracking & management through Google Sheets

🔧 Tech Stack:
n8n - Open-source workflow automation tool

Google Sheets API

Email (SMTP) integration

📁 Files Included:
cold-email-workflow.json – n8n exportable workflow

README.md – Setup & usage instructions

cold email.csv – Template for your Google Sheet

🚀 How to Use:
Import the workflow into your local or cloud-hosted n8n instance

Connect Google Sheets and Email credentials

Replace placeholder fields in the Sheet (e.g., [name], [your name])

Deploy and let it run on schedule

