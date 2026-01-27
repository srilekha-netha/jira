# 🧠 AI-Powered Jira Defect Writing Tool

An AI-powered Streamlit application that automatically generates well-structured Jira defect reports from user stories and issue descriptions. Designed to help QA engineers create professional Jira defects quickly and consistently.

---

## ✨ Features

- Automatically generates complete Jira defect reports
- Standard Jira format:
  - Title
  - Issue Description
  - Steps to Reproduce
  - Expected Result
  - Actual Result
  - Plan ID
  - Group ID
- Sprint, Module, and Environment-based defect creation
- AI-powered using OpenRouter (GPT model)
- Export defects as Word (.docx) files
- Simple and user-friendly Streamlit UI

---

## 🛠 Tech Stack

- Python
- Streamlit
- OpenRouter API
- python-docx
- dotenv
- requests

---

## 📁 Project Structure

<img width="232" height="162" alt="image" src="https://github.com/user-attachments/assets/45e2249f-cec9-4d24-b6ab-ff02276dca85" />

---
# Install Dependencies
pip install -r requirements.txt
# Run the Application
streamlit run app.py
