# Data Analyst Agent

An AI-powered data analysis automation built with n8n that turns natural language queries into structured insights, visual analytics, and executive-ready summaries delivered straight to your inbox.

---

## Project Overview

The **Data Analyst Agent** is designed to act like a virtual data analyst. You ask a question in plain English, and the agent retrieves relevant records from Google Sheets, analyzes the data, generates insights, creates charts, and sends a polished analytical report via email.

It is especially useful for analyzing professional profile data such as roles, companies, and locations, without writing SQL, formulas, or code.

---

## What This Automation Does

- Accepts a natural-language query through chat  
- Interprets roles, locations, and filters using an AI agent  
- Fetches matching records from Google Sheets  
- Cleans and structures the extracted data  
- Generates an executive-style narrative summary  
- Builds bar, line, and pie charts automatically  
- Sends a complete analysis report via Gmail  

---

## Key Features

- Natural language data querying  
- AI-powered data interpretation and summarization  
- Automatic data cleaning and validation  
- Dynamic chart generation using QuickChart  
- Executive-ready written insights (no raw JSON)  
- Email delivery with embedded charts  
- Memory support for short conversational context  

---

## Tools Used

- **n8n** for workflow orchestration  
- **OpenAI (GPT-4.1 & GPT-4.1-mini)** for reasoning and reporting  
- **Google Sheets** as the data source  
- **QuickChart** for visual analytics  
- **Gmail API** for automated email delivery  
- **LangChain Memory** for short-term conversational context  

---


## Workflow JSON File

You can import this workflow directly into n8n.

**Workflow File:**  

`Data Analyst Agent.json`

### Import Steps

1. Open n8n  
2. Go to **Settings → Import workflow**  
3. Upload the JSON file

---

## Workflow Architecture

1. **Chat Trigger**  
   Receives the user’s natural-language query.

2. **AI Agent (Search Interpreter)**  
   Extracts role, location, and filters and returns structured data from Google Sheets.

3. **Data Cleaning Node**  
   Normalizes and validates AI output into clean labels and values.

4. **Report Writer (GPT-4.1)**  
   Generates a concise, professional narrative summary.

5. **Analytics & Visualization Engine**  
   Aggregates data, identifies patterns, and creates bar, line, and pie charts.

6. **Email Composer**  
   Formats insights and charts into a clean HTML email.

7. **Gmail Sender**  
   Delivers the final analysis report to the recipient.

---

## Workflow Output

- Plain-English analytical summary  
- Company or category distribution insights  
- Bar chart showing counts by company  
- Line chart for trend-style comparison  
- Pie chart for proportional distribution  
- Fully formatted HTML email report

### Full Workflow Overview

<img width="1871" height="826" alt="workflow" src="https://github.com/user-attachments/assets/54bf9f6b-0184-44c8-a5a0-e06d126a77c3" />

-  **Output**

<img width="1534" height="721" alt="output" src="https://github.com/user-attachments/assets/5d9012b1-389e-4ea6-9373-b41526aeeb3e" />

---

## Use Cases

- Talent and recruitment analysis  
- Executive or leadership market mapping  
- Hiring pipeline insights  
- Sales and prospect research  
- Market or industry concentration analysis  
- Internal reporting without dashboards  

---

## 👤 Author

Muqadas Ejaz

BS Computer Science (AI Specialization)

AI/ML Engineer

Data Science & Gen AI Enthusiast

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

📬 Kaggle: [Kaggle Profile](https://www.kaggle.com/muqaddasejaz) 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

 If you find this project useful, don’t forget to star ⭐ the repository!
