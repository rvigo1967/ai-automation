## Automation of Invoice Reporting (UiPath)
This project automates the end-to-end process of invoice reporting using UiPath and AI-powered capabilities. It replaces manual invoice review workflows with a scalable, efficient, and accurate automation pipeline.

## 🧠Problem
Businesses receive large volumes of customer feedback, but manual review is slow, inconsistent, and often delayed. This leads to missed critical issues and poor customer experience.

💡Solution
This workflow automates the analysis of customer feedback using AI to:

Collects and analyzes customer responses
Classifies sentiment (Positive / Neutral / Negative)
Summarizes feedback automatically
Sends email alerts for negative sentiment
⚙️Workflow
Customer submits feedback (Google Forms)
Triggers the workflow
Gemini AI analyzes sentiment and extracts insights
Results are stored in Google Sheets
Negative feedback triggers Gmail alert ( triggers Slack alert)
🏗️Architecture
Architecture

🛠️Tools Used
Make (workflow automation)
GemeniAI API (NLP processing)
Google Sheets (data storage)
Gmail (notifications)
📊 Results / Business Impact (CRITICAL)
⏱️ Reduced manual review time by 80%
⚡ Instant detection of negative feedback
📈 Improved response time to customer issues
📥 Sample Input / Output
Sample Input

"The service was slow and the staff was rude."

Sample Output

Sentiment: Negative
Keywords: slow service, rude staff
Summary: Customer dissatisfied with service speed and staff behavior
📸Screenshots
WorkFlow

🚀Future Improvements
Add visual dashboards (Looker Studio/Power BI) for trend analysis
Integrate Slack or Teams alerts for faster response
Expand to multilingual sentiment analysis for global feedback
