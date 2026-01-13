🤖 MCP-Based Lead Qualification Chatbot (n8n + AI)

An AI-powered lead qualification and site-visit scheduling chatbot built using n8n, MCP Client–Server architecture, and Google Gemini.
The system automates user interaction, qualifies real-estate leads, schedules site visits, and stores structured data in Google Sheets.

📌 Project Overview

This project demonstrates how AI agents + low-code automation can be combined to build an intelligent conversational system for real-estate lead management.

The chatbot:

Interacts with users in natural language

Collects lead details (name, mobile number, requirement)

Confirms site visit date & time

Stores the qualified lead automatically in Google Sheets

✨ Key Features

💬 AI-powered conversational chatbot

🧠 Context-aware responses using memory

🔗 MCP Client–Server communication

📅 Automated site visit scheduling

📊 Lead storage in Google Sheets

⚡ Fully automated n8n workflows

🏗️ System Architecture
User Chat
   ↓
n8n Chat Trigger
   ↓
AI Agent (Google Gemini + Memory)
   ↓
MCP Client
   ↓
MCP Server
   ↓
Google Sheets (Lead Storage)

⚙️ Tech Stack

n8n – Workflow Automation

Google Gemini Chat Model – AI responses

MCP Client & MCP Server – Data communication

Google Sheets – Lead storage

Simple Memory – Conversation context

📂 Project Structure
MCP_Lead_Qualification_Chatbot/
│
├── screenshots/
│   ├── client_workflow.png
│   ├── server_workflow.png
│   ├── chat_execution.png
│   ├── workflow_overview.png
│   └── google_sheet_output.png
│
├── workflows/
│   ├── MCP_Client_Lead_Qualification.json
│   └── MCP_Server_Lead_qualification.json
│
└── README.md

🔄 Workflow Details
1️⃣ MCP Client – Lead Qualification Workflow

This workflow handles user interaction and lead qualification.

What it does:

Receives chat messages

Uses AI Agent (Google Gemini) to respond

Collects:

👤 Name

📞 Mobile Number

🏠 Property Type (2BHK / 3BHK)

⏰ Site visit date & time

Sends structured data to MCP Server

📸 Client Workflow (n8n Editor)

2️⃣ MCP Server – Lead Storage Workflow

This workflow stores qualified leads in Google Sheets.

What it does:

Receives lead data from MCP Client

Appends a new row in Google Sheets

Ensures persistent lead tracking

📸 Server Workflow (n8n Editor)

💬 Chat Execution & Logs

Below screenshots show:

Real-time chat interaction

AI-generated confirmation message

Successful execution logs inside n8n

📸 Chat Execution & Logs

📊 Workflow Overview Dashboard

This screen shows:

Workflow execution count

Success rate

Active client & server workflows

📸 Workflow Overview

📈 Google Sheets – Lead Storage Output

All qualified leads are automatically stored with:

Name

Date

Time

User requirement

Mobile number

📸 Google Sheets Output

🚀 How to Run This Project

Import both workflows into n8n

Configure credentials:

Google Gemini API

Google Sheets API

Activate:

MCP_Client_Lead_Qualification

MCP_Server_Lead_qualification

Start chatting using the n8n chat interface

🎯 Use Cases

🏠 Real-estate lead qualification

📅 Appointment scheduling bots

🤖 AI customer support

📊 CRM data automation

📌 Future Enhancements

SMS / WhatsApp notifications

CRM integration (HubSpot, Salesforce)

Lead scoring with AI

“MCP Client Workflow – Lead Qualification Chatbot”

<img width="959" height="407" alt="chatbot" src="https://github.com/user-attachments/assets/dd9d26b7-5238-4178-af76-3abebf7ed87d" />


" MCP Server Workflow "
<img width="954" height="446" alt="chatbot5" src="https://github.com/user-attachments/assets/dc51211f-4ab1-4556-aef6-fb93a694b02b" />


<img width="905" height="442" alt="chatbot4" src="https://github.com/user-attachments/assets/87ac0ab5-ed6b-4e1b-9507-5baa30c0e593" />
<img width="956" height="446" alt="chatbot2" src="https://github.com/user-attachments/assets/6913b05f-20cf-4a18-bbcb-31090eb789fa" />
<img width="959" height="479" alt="chatbot3" src="https://github.com/user-attachments/assets/7fe2c6f2-7e5d-47bd-b32a-dc99e3eb218f" />



