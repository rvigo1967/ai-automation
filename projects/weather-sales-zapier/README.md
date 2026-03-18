## Automation of Weather-Based Sales and Staffing Decisions (Zapier)
This project automates daily business decision-making for a small kiosk, by leveraging weather data and AI.

## 🧠Problem

Bayside Brews & Scoops relied on manual weather checks to make daily decisions. This process was:
  - Time-consuming
  - Inconsistent
  - Prone to human error
    
 The business needed an automated solution to deliver reliable, data-driven insights every day.

## 💡Solution

**An automated workflow that:**

1. Runs daily at 7:00 AM
2. Retrieves Miami weather data using OpenWeather API
3. Sends the data to Gemini AI for interpretation
4. Generates:

      - Product recommendations
      - Staffing suggestions
      - Two promotional messages
      - Emails a structured summary to the manager

⚠️ Severe weather conditions trigger an additional alert for quick preparation.

## ⚙️Workflow
Main Components:

- Trigger: Scheduled automation (Zapier)
- Data Source: OpenWeather API
- AI Processing: Google Gemini
- Formatting: Zapier Formatter
- Output: Email notification
  
## 🏗️Architecture
![Architecture](./architecturediagram1.png)

## 🛠️Tools Used

- Zapier (workflow automation)
- GemeniAI API (NLP processing)
- OpenWeather API (Data Source)
- Gmail (notifications)

## 📈 Benefits

**1. Faster, Data-Driven Decisions**
   - Eliminates manual weather checks
   - Provides consistent AI-powered recommendations
     
**2. Increased Operational Efficiency**
   - Reduces time spent on planning
   - Minimizes human error
     
**3. Higher Sales Potential**
   - Aligns product offerings with weather demand
   - Improves promotional targeting

## 📸Screenshots
![Workflow](./zapierworkflow.png)

## Areas for Improvement

**1. API Setup Complexity**
  - **Issue:** OpenWeather API setup required manual configuration
  - **Improvement:** Use reusable API templates, Consider native Zapier integrations.

**2. AI Output Formatting**

  - **Issue:** Inconsistent AI responses
  - **Improvement:** Use structured JSON prompts, Standardize output fields.

**3. Error Handling**

  -**Issue:** Workflow continues even if failures occur
  - **Improvement:** Add validation filters, Use conditional paths for missing data.
