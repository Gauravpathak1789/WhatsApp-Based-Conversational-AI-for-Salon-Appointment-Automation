💇‍♀️ SalonAI – WhatsApp-Based Conversational AI for Salon Appointment Automation

An end-to-end WhatsApp-based Conversational AI system designed to automate salon customer interactions, service recommendations, and appointment management using n8n workflows and LLM-powered intelligence.

🚀 Project Overview

SalonAI is an intelligent virtual assistant that allows customers to interact with a beauty salon directly via WhatsApp.
It automates the complete appointment lifecycle — from booking to rescheduling and cancellation — while synchronizing data across CRM and calendar systems in real time.

This project demonstrates real-world AI automation, conversational flow design, and workflow orchestration using no-code/low-code tools combined with LLMs.

📅 Duration: August 2025 – September 2025
🛠️ Platform: n8n Automation Engine
📲 Interface: WhatsApp Business API

🎯 Objectives

Automate salon appointment booking via WhatsApp

Provide intelligent, personalized service recommendations

Eliminate manual scheduling and follow-ups

Maintain a centralized CRM and calendar system

Deliver a human-like conversational experience using LLMs

✨ Key Features
💬 Conversational AI (WhatsApp)

Natural language interaction with customers

Friendly, human-like responses

Multistep guided booking flows

🧠 Intelligent Intent Detection

Detects user intent such as:

New booking

Reschedule appointment

Cancel appointment

Service inquiry

Context-aware conversation handling using memory buffers

📅 Real-Time Appointment Management

Checks real-time availability via Google Calendar

Prevents double booking

Automatically calculates service durations and time slots

🗂️ Automated CRM Management

Customer registration and lookup in Airtable

Tracks:

Customer details

Appointment history

Status (Confirmed / Cancelled)

🔁 Full Appointment Lifecycle Automation

Create: Airtable + Google Calendar

Update: Reschedule with calendar sync

Delete: Cancel appointment and remove calendar event

🧾 Conversation Logging

Maintains conversation context across messages

Ensures continuity even if the user pauses or returns later

🏗️ System Architecture
WhatsApp User
     ↓
WhatsApp Business API
     ↓
n8n Workflow Engine
     ↓
Gemini LLM (Intent + Response)
     ↓
Airtable (CRM & Appointments)
     ↓
Google Calendar (Availability & Events)

🧰 Technologies Used
Category	Tools
Automation	n8n
LLM	Google Gemini
Messaging	WhatsApp Business API
Database / CRM	Airtable
Calendar	Google Calendar
Data Tracking	Google Sheets
📚 Learning Outcomes

Designing real-world conversational AI workflows

Intent classification and context management

Integrating LLMs with automation tools

Building production-grade appointment systems

Synchronizing CRM and calendar data reliably

Handling edge cases (time zones, availability conflicts)

🧪 Example Use Cases

“Hi, I want to book a manicure tomorrow”

“Can I reschedule my appointment?”

“Cancel my lashes appointment”

“What services do you offer and their prices?”

All handled automatically without human intervention.

🔐 Best Practices Followed

One-question-at-a-time conversational rule

Strong separation between tool calls and user messages

Reliable ID-based updates for Airtable & Calendar

Consistent date/time formatting and timezone handling

Fail-safe flows for no availability or invalid inputs

📌 Future Enhancements

Payment integration (Razorpay / Stripe)

Multilingual expansion

Analytics dashboard for salon owners

Staff assignment automation

Customer feedback collection
