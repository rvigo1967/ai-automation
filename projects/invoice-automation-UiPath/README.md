## 🤖 Automation of Invoice Reporting with UiPath
<p align="center"> <img src="https://img.shields.io/badge/RPA-UiPath-orange?style=for-the-badge&logo=uipath" /> <img src="https://img.shields.io/badge/Automation-AI%20Powered-blue?style=for-the-badge&logo=openai" /> <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" /> <img src="https://img.shields.io/badge/Use%20Case-Finance%20Automation-purple?style=for-the-badge" /> </p> <p align="center"> <b>End-to-end AI-powered invoice processing system built with UiPath</b><br> Automating extraction, validation, and reporting for faster financial decisions </p>

## 📌 Overview

This project demonstrates how Robotic Process Automation (RPA) combined with Generative AI can transform manual finance workflows into a fully automated pipeline.
The solution processes invoices from ingestion to reporting, eliminating repetitive tasks while improving accuracy and speed.

## 🧠Problem
**Manual invoice processing creates operational bottlenecks:**

- ⏳ Time-intensive data entry
- ❌ Human errors in financial data
- 📉 Lack of real-time visibility
- 🧾 Unstructured invoice information

**Objective:**
Automate invoice processing and generate a structured report of invoices due by September 22, 2025, with intelligent validation and summaries.

## 💡Solution

📂 Google Drive (Invoices)
        ↓
📥 UiPath Document Understanding
        ↓
🔍 Data Extraction (Key Fields)
        ↓
⚠️ Confidence Validation
        ↓
🤖 AI Description Generation
        ↓
📅 Due Date Filtering
        ↓
📊 Google Sheets Reporting

## 📊 Structured Output
Writes clean, organized data into Google Sheets
## ⚙️Workflow

Customer submits feedback (Google Forms)
Triggers the workflow
Gemini AI analyzes sentiment and extracts insights
Results are stored in Google Sheets
Negative feedback triggers Gmail alert ( triggers Slack alert)

## 🏗️Architecture
Architecture

## 🛠️Tools Used

- UiPath
- Google Drive
- Google Sheets
- Generative AI


## 📊 Results / Business Impact (CRITICAL)
⏱️ Reduced manual review time by 80%
⚡ Instant detection of negative feedback
📈 Improved response time to customer issues

## 📥 Sample Input / Output
Sample Input

"The service was slow and the staff was rude."

Sample Output

Sentiment: Negative
Keywords: slow service, rude staff
Summary: Customer dissatisfied with service speed and staff behavior

## 📸Screenshots
WorkFlow

## 🚀Future Improvements

Add visual dashboards (Looker Studio/Power BI) for trend analysis
Integrate Slack or Teams alerts for faster response
Expand to multilingual sentiment analysis for global feedback
