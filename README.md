# 🤖 Personal AI Agent with n8n

This project showcases a powerful **Personal AI Agent** built using n8n.io, the fair-code workflow automation tool. It acts like a virtual assistant that can read data from Google Sheets, respond using OpenAI, and automate tasks intelligently — all without writing traditional code.

---

## 🚀 Features

- 🧠 Connects with OpenAI for smart conversational responses
- 📄 Reads inventory or task data from Google Sheets
- ⏱️ Can be triggered manually, via webhook, or on a schedule
- 🔁 Automates repetitive actions based on input (e.g., low stock alerts)
- 🔗 Easily extendable to Notion, Telegram, Slack, Gmail, or any API

---

## 🛠️ Tech Stack

- Google Sheets API
- Webhooks, Triggers, and Conditional Logic

---

## 🧩 How It Works

1. **Trigger Node** (Manual/Webhook/Cron) initiates the workflow
2. **Google Sheets Node** reads input data like `Item Name` and `Quantity`
3. **Function/IF Node** checks conditions (e.g., if quantity < 10)
4. **OpenAI Node** generates a response or summary
5. **Notification Node** (e.g., Telegram or Gmail) sends an alert or message

---

## 🧪 Demo Use Case
<img width="1920" height="1032" alt="Screenshot 2025-07-22 024441" src="https://github.com/user-attachments/assets/8c0d445a-7b5d-402d-9718-47237db0c4b7" />



> "Check my inventory, and alert me if any item is low stock."

The agent reads your Google Sheet, checks stock levels, and sends you a message like:

