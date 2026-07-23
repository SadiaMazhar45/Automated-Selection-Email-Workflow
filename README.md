# 📧 Automated Selection Email Workflow (n8n)

This project is an **n8n workflow** that automates the process of sending selection emails. It reads applicant data from Google Sheets, filters eligible candidates, sends personalized emails via Gmail, and updates the spreadsheet with the email status. :contentReference[oaicite:0]{index=0}

## ✨ Features

- 📄 Reads applicant data from Google Sheets
- ✅ Filters selected candidates who haven't been emailed
- 📧 Sends personalized selection emails using Gmail
- 📝 Marks successful emails as "Sent"
- ⚠️ Logs failed email attempts with error details

## 🛠️ Tech Stack

- n8n
- Google Sheets API
- Gmail API

## 🔄 Workflow

```text
Manual Trigger
      │
      ▼
Read Applicants from Google Sheets
      │
      ▼
Filter Selected & Not Emailed
      │
      ▼
Send Selection Email
      │
 ┌────┴────┐
 ▼         ▼
Mark Sent  Log Error
```

## 📷 Workflow Preview

![Workflow](screenshots/workflow.png)

## 📄 License

This project is intended for educational and automation purposes.
