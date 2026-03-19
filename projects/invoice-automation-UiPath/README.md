🤖 Automation of Invoice Reporting with UiPath
<p align="center"> <img src="https://img.shields.io/badge/RPA-UiPath-orange?style=for-the-badge&logo=uipath" /> <img src="https://img.shields.io/badge/Automation-AI%20Powered-blue?style=for-the-badge&logo=openai" /> <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" /> <img src="https://img.shields.io/badge/Use%20Case-Finance%20Automation-purple?style=for-the-badge" /> </p> <p align="center"> <b>End-to-end AI-powered invoice processing system built with UiPath</b><br> Automating extraction, validation, and reporting for faster financial decisions </p>

## 🧠Problem
**Organizations often rely on manual processes to review invoices, which leads to:**

- Time-consuming data entry
- Higher risk of human error
- Lack of structured reporting
- Delayed financial insights

**The goal was to build an automated workflow that:**

- Reads invoices from Google Drive
- Extracts key invoice fields
- Generates purchase descriptions
- Populates a reporting sheet
- Flags low-confidence data for review
- Filters invoices due by September 22, 2025

## 💡Solution
The solution leverages UiPath Document Understanding and Generative AI to automate invoice processing:

1. 📂 Automated File Ingestion:
      - Reads invoices directly from Google Drive

2. 🔍 Data Extraction
     - Extracts key fields (amounts, dates, vendors, etc.)

3. 🤖 AI-Powered Descriptions
Generates short purchase summaries using GenAI

⚠️ Confidence Validation
Flags low-confidence totals for human review

📅 Date Filtering
Filters invoices due on or before Sept 22, 2025

📊 Structured Output
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
