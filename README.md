# 🤖 AI Resume vs Job Description Matcher

## 📌 Project Overview

This project is an AI-powered workflow built with **n8n** that compares a candidate's resume against a job description. Using a Large Language Model (LLM), it analyzes the resume and provides structured feedback, including strengths, weaknesses, and recommendations to help improve the candidate's fit for the role.

This workflow demonstrates how AI can automate resume evaluation and assist recruiters or job seekers with faster and more consistent assessments.

## ✨ Features

- Compare a resume against a job description using AI
- Generate strengths based on the candidate's qualifications
- Identify weaknesses or missing skills
- Provide AI-generated recommendations for improvement
- Return structured JSON output using the Structured Output Parser
- Built entirely in n8n with AI Agent integration

## 🔄 Workflow

The workflow compares a resume with a job description using an AI Agent. The resume and job description are merged into a single input, analyzed by the AI model, and returned as structured feedback using a Structured Output Parser.

![Workflow Overview](screenshots/01-workflow-overview.png)

## 📝 Sample Input

The workflow accepts two text inputs before sending them to the AI Agent.

### 📄 Resume Input

This node contains the candidate's resume information used for analysis.

![Resume Input](screenshots/02-resume-input.png)

### 💼 Job Description Input

This node contains the job requirements that will be compared against the candidate's resume.

![Job Description Input](screenshots/03-job-description-input.png)

## 🤖 AI Analysis

After receiving the resume and job description, the AI Agent analyzes both inputs and generates structured feedback. The analysis includes the candidate's strengths, weaknesses, and recommendations for improving their fit for the position.

![AI Analysis](screenshots/04-ai-analysis.png)

## ✅ Workflow Execution

The screenshot below shows a successful execution of the workflow in n8n. All nodes completed successfully, demonstrating the end-to-end automation from data input to AI-generated analysis.

![Workflow Execution](screenshots/05-workflow-execution.png)

## 🛠 Technologies Used

- **n8n** – Workflow automation platform
- **Groq API** – AI inference provider
- **Llama 3.3 70B Versatile** – Large Language Model
- **AI Agent Node** – AI orchestration
- **Structured Output Parser** – Consistent JSON responses
- **JSON** – Data format

## 🚀 Future Improvements

- Support PDF and DOCX file uploads
- Add an ATS compatibility score
- Highlight missing skills automatically
- Generate an improved resume based on AI recommendations
- Integrate with Applicant Tracking Systems (ATS)

## 👨‍💻 Author

**Ryan S. Brecia**

Aspiring AI Automation Specialist passionate about building AI-powered business workflows using **n8n**, **Groq AI**, and modern automation tools.

Connect with me on GitHub to explore more AI automation projects.



