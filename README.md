# 🎯 Interview Trainer Agent
### IBM SkillsBuild University Engagement | AICTE 2026 | Problem Statement No. 22

An AI-powered mock interview coach built using **LangFlow** and **IBM watsonx.ai** 
that prepares students for job interviews through personalized question generation, 
real-time feedback, and session scoring.

---

## 🚀 What It Does
- Takes user's **job role and experience level** as input
- Generates **5 targeted interview questions** (technical + behavioral)
- Conducts a **live mock interview** — one question at a time
- Gives **real-time feedback** on every answer (strengths, improvements, model answer)
- Provides a **final session summary** with score out of 10

---

## 🛠️ Tech Stack
| Technology | Purpose |
|---|---|
| LangFlow | Visual agent workflow builder |
| IBM watsonx.ai | LLM hosting and API endpoint |
| IBM Granite (intended) | Mandatory model requirement |
| Meta Llama 3.3 70B | Used via IBM watsonx.ai (instructor approved) |
| IBM Cloud Lite (au-syd) | Free-tier infrastructure |
| Message History | Conversation memory across session |

---

## 📁 Repository Files
- `app.json` — LangFlow flow export (import this to run the agent)
- `Jasmeet_AIInterviewAgent.pptx` — Project presentation
- `SB4UniversityEngagements_AICTE_Problem_Statements_2026.pdf` — Problem statement
- `langflow_workflow.png` — LangFlow canvas screenshot

---

## ▶️ How to Run
1. Install LangFlow: `pip install langflow` then `langflow run`
2. Open `http://localhost:7860`
3. Import `app.json` into LangFlow
4. Add your IBM watsonx.ai API key and Project ID
5. Click **Playground** and type your job role to start!

---

## 👩‍💻 Submitted By
**Jasmeet Kaur** | jasmeetkaur8206@gmail.com  
IBM SkillsBuild Internship | AICTE 2026
