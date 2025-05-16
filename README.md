# 🤖 AI-Powered Customer Feedback Automation Agent

An intelligent automation workflow designed using **n8n** that collects customer feedback, analyzes it with **Google Gemini**, categorizes it, and sends the feedback to the appropriate team in **Slack**, stores it in **Airtable**, and sends a personalized email response back to the customer  all without human intervention.

---

## 🚀 Project Summary

This AI agent simulates a real-world automated support system. It automates end-to-end feedback management, improving customer response time and internal team coordination.

---

## 🧠 Key Features

- Collects **customer feedback** via form or webhook
- Uses **Google Gemini** to analyze sentiment and intent
- Categorizes feedback into:
  - 🔴 Complaint
  - 🟢 Compliment
  - 🟡 Feature Request
- Sends categorized messages to **Slack** teams
- Logs records in **Airtable** for tracking
- Sends **personalized email** replies to customers via **Gmail**
- Fully **automated**, no manual effort required

---

## 🏗️ Tech Stack

| Tool           | Role                                     |
|----------------|------------------------------------------|
| `n8n`          | No-code/low-code workflow orchestrator   |
| `Google Gemini`| AI feedback analysis & classification    |
| `Slack`        | Sends categorized messages to teams      |
| `Airtable`     | Logs feedback records for tracking       |
| `Gmail`        | Sends customized replies to customers    |

---

## 🖼️ Workflow Architecture

<div align="center">
  <img src="https://github.com/user-attachments/assets/32eabaaf-95e5-4cb0-853c-fdcdca719b1f" width="600" alt="CF Agent Flowchart">
</div>

---

## 📌 Workflow Image

<div align="center">
  <img src="https://github.com/user-attachments/assets/ff1d3c1c-e9b0-4067-9050-66061f6fef9f" width="600" alt="Workflow Screenshot">
</div>


## 📸 Demo Screenshots

<h2 align="center">💬 Slack Messages per Feedback Type</h2>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d81aaa36-02a0-46cd-9ef4-47a387e7bdf0" width="200px"><br>
      <strong>Product/Dev Team</strong>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/93de232a-9295-48b5-956c-0f6f9683c525" width="200px"><br>
      <strong>General Team</strong>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a4faa298-8baa-449a-91c9-4e50749b6fb6" width="200px"><br>
      <strong>Customer Support</strong>
    </td>
  </tr>
</table>

<br>

<h2 align="center">📊 Airtable Feedback Record Entries</h2>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c7f9b8ac-7dca-4c44-96a2-41dea4fd11da" width="200px"><br>
      <strong>Complaint Record</strong>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c4a533df-ce0d-4b3a-86c7-d7658f1d3369" width="200px"><br>
      <strong>Compliment Record</strong>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/06f6f252-fbd7-436c-8419-29173e2283b1" width="200px"><br>
      <strong>Feature Request</strong>
    </td>
  </tr>
</table>

<br>

<h2 align="center">📧 Email Auto-Response Previews</h2>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/68095bb6-a338-4c0c-be6b-09cad3ae5cf7" width="200px"><br>
      <strong>Mailed to Abhinav</strong>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/eb86e2eb-7f53-4e01-9f91-fb1553656bad" width="200px"><br>
      <strong>Mailed to Rajesh</strong>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/f38cf3c7-1c92-40aa-a444-6fe2342fd530" width="200px"><br>
      <strong>Mailed to Arman</strong>
    </td>
  </tr>
</table>
- 

---

## 🔧 How to Use (Developer Guide)

1. **Clone or Import Workflow**
   - Save your workflow `.json` file and import into your n8n instance

2. **Set Up APIs & Credentials**
   - **Google Gemini API**
   - **Slack Bot Token**
   - **Gmail API** (OAuth2 or SMTP config)
   - **Airtable API Key** and **Base/Table IDs**

3. **Test the Workflow**
   - Trigger manually or via webhook
   - View Slack messages, email replies, and Airtable entries

---

## 💡 Use Cases

- SaaS customer support automation  
- Product feedback triage system  
- Customer sentiment tracking  
- Internal escalation and logging tool

---

## 📌 Project Highlights

- Developed using **n8n (Cloud trial mode)**
- Integrated **Gemini AI** for advanced language analysis
- Real-time Slack delivery ensures immediate team awareness
- Response emails improve **customer satisfaction**
- Modular and extensible for future additions like:
  - CRM integration (HubSpot, Salesforce)
  - Ticket generation
  - WhatsApp or Telegram notification

---

## 📁 Storage & Portability

If you're using n8n cloud trial and can't find an "Export" button:
1. Press `...` on top of workflow editor
2. Click the Downlode option
3. Add the file to this repo or save in your personal drive
---

## ✨ Future Improvements

- Add sentiment score weighting
- Generate unique support ticket IDs
- Build a web frontend to input and visualize feedback
- Integrate voice/text inputs via WhatsApp or chat widgets

---

## 🧑‍💻 About Me

I’m **Abhinav**, a passionate full-stack developer transitioning into automation development. With a solid foundation in **React**, **javascript**, and **Node.js**, I’m now working on intelligent automation tools using platforms like **n8n** and exploring **AI-powered SaaS** ideas.

---

## 🌐 Connect with Me

- 🔗 [LinkedIn](https://www.linkedin.com/in/abhinav-patel-974852244/)  
- 🐙 [GitHub](https://github.com/abhinav-patel887)  
- 📧 gunnammagariabhinavpatel@gmail.com  

---

> 🏁 If you’re an HR, recruiter, or dev looking to collaborate or explore automation, feel free to connect!

