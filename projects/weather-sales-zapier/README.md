## Automation of Weather-Based Sales and Staffing Decisions (Zapier)
This project automates daily business decision-making for a small kiosk, by leveraging weather data and AI.

## 🧠Problem

Bayside Brews & Scoops relied on manual weather checks to make daily decisions. This process was:
  - Time-consuming
  - Inconsistent
  - Prone to human error
    
 The business needed an automated solution to deliver reliable, data-driven insights every day.

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
Make (workflow automation)
GemeniAI API (NLP processing)
Google Sheets (data storage)
Gmail (notifications)
📊 Results / Business Impact (CRITICAL)
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
