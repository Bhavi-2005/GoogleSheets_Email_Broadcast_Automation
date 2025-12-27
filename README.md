# 📧 Google Sheets Email Broadcast Automation (n8n)

This project is an **n8n automation workflow** that sends bulk emails using **Google Sheets** and **Gmail**.  
A simple form is used to enter the email subject and message, which are then sent automatically to all email addresses listed in a Google Sheet.

---

## 🚀 What This Automation Does

- Collects email subject and message using an n8n Form Trigger
- Reads recipient email addresses from a Google Sheet
- Sends the email to all recipients using Gmail
- Eliminates manual bulk emailing

---

## 🔄 Workflow Overview

1. **Form Trigger**
   - User enters:
     - Email Subject
     - Email Message

2. **Google Sheets**
   - Fetches email addresses from a specified sheet

3. **Gmail**
   - Sends the email to each address from the sheet

---

## 📊 Google Sheet Format (Required)

The Google Sheet must contain the following column:

| E-mail |
|-------|
| example1@gmail.com |
| example2@gmail.com |
| example3@gmail.com |

⚠️ The column name must match exactly as used in the workflow.

---

## 🧩 Nodes Used

- Form Trigger
- Google Sheets
- Gmail

---

## 🔐 Credentials Required

Before running the workflow, configure the following credentials in n8n:

- Google Sheets OAuth2
- Gmail OAuth2

---

## ▶️ How to Use

1. Import the workflow JSON into n8n
2. Set up Google Sheets and Gmail credentials
3. Open the Form Trigger URL
4. Enter the email subject and message
5. Submit the form
6. Emails will be sent to all recipients in the sheet

---

## 🎯 Use Cases

- Announcements
- Internship or college updates
- Event notifications
- Small-scale newsletters
- Internal communication

---

## ⚠️ Limitations

- Gmail sending limits apply
- No email templates
- No analytics or tracking
- No unsubscribe handling

---

## 📁 Workflow File

The complete n8n workflow JSON is included in this repository and can be imported directly into n8n.

---

## 👤 Author

**Bhavi**  
Automation & Full Stack Development Learner  
Building practical workflow automations using n8n
