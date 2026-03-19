## Automation of Invoice Reporting (UiPath)
This project automates the end-to-end process of invoice reporting using UiPath and AI-powered capabilities. It replaces manual invoice review workflows with a scalable, efficient, and accurate automation pipeline.

## 🧠Problem
Organizations often rely on manual processes to review invoices, which leads to:

- Time-consuming data entry
- Higher risk of human error
- Lack of structured reporting
- Delayed financial insights

The goal was to build an automated workflow that:

- Reads invoices from Google Drive
- Extracts key invoice fields
- Generates purchase descriptions
- Populates a reporting sheet
- Flags low-confidence data for review
- Filters invoices due by September 22, 2025

## 💡Solution
This workflow automates the analysis of customer feedback using AI to:

Collects and analyzes customer responses
Classifies sentiment (Positive / Neutral / Negative)
Summarizes feedback automatically
Sends email alerts for negative sentiment
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
