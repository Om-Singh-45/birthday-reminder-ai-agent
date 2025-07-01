# 🎉 Birthday Reminder AI Agent via WhatsApp

This project automates birthday reminders using **n8n**, sending WhatsApp messages through **Twilio**, with contact data managed in **Google Sheets**.

## ⚙ Tech Stack
- 🛠️ [n8n](https://n8n.io) – No-code workflow automation
- 📱 [Twilio API](https://www.twilio.com/whatsapp) – WhatsApp messaging
- 📊 Google Sheets API – For storing contact and birthday data
- 🧠 Code Node (JavaScript) – To format messages and calculate birthdays

## 🧩 Workflow Overview
1. **Schedule Trigger** – Runs daily
2. **Get Rows from Google Sheets** – Fetches contact list
3. **Code Node** – Checks today's birthdays
4. **HTTP Request (Twilio API)** – Sends WhatsApp wishes

## 📂 Files
- `birthday_reminder_workflow.json` – n8n workflow export
- `.env.example` – Environment variable placeholders (Twilio SID, Auth Token, etc.)

## 🔐 Setup (Optional)
If you're running n8n locally or on a server:
1. Set your `.env` file with:
2. Import the JSON in n8n.
3. Schedule the workflow to run daily.

## 📽 Demo
https://www.linkedin.com/posts/om-singh5_n8nautomation-workflowwizard-twiliowhatsapp-activity-7343228992184840195-JyFU?utm_source=share&utm_medium=member_desktop&rcm=ACoAADu8f_0BABLTy3Tj6pEk3nQgn2l6e9IHekM

## 📌 Use Cases
- Personal birthday reminders
- HR automation
- Client engagement workflows

![Screenshot 2025-06-24 163753](https://github.com/user-attachments/assets/a981abf9-8c80-44e5-8ca1-1067a3df3a66)
![Screenshot 2025-06-24 163625](https://github.com/user-attachments/assets/6736a858-eb59-40cd-a43a-9983a01c9e56)
![Screenshot 2025-07-02 012954](https://github.com/user-attachments/assets/cd164d54-b713-4dd9-b4bd-7dce8801244a)

