# 🚀 n8n AI Tagging Workflow

## 📌 Project Overview

This project is an automation workflow built using **n8n** that processes form submissions, validates email domains, and generates AI-powered content tags using OpenAI.

It is designed to demonstrate how automation and AI can be combined to streamline data processing and categorization tasks.

---

## ⚙️ Features

* ✅ Form submission trigger
* ✅ Email validation (Gmail domain check)
* ✅ Conditional logic using IF node
* ✅ AI-powered tag generation (OpenAI)
* ✅ Structured data insertion (e.g., database / sheets)

---

## 🧠 How It Works

1. A user submits a form
2. The system checks if the email is valid (`@gmail.com`)
3. Based on the condition:

   * ✔ True → Process continues
   * ❌ False → Alternative path
4. AI generates relevant tags from the content
5. Data is stored in a structured format

---

## 🛠️ Tech Stack

* n8n (Workflow Automation)
* OpenAI API (AI Tag Generation)

---

## 📂 Project Structure

```text
workflow.json   → Main n8n workflow file
README.md       → Project documentation
```

---

## 🚀 How to Use

### 1. Import Workflow

* Open n8n
* Click **Import from file**
* Upload `workflow.json`

### 2. Configure Credentials

* Add your OpenAI API key
* Configure any required integrations

### 3. Run Workflow

* Execute manually or activate workflow
* Submit test data via form

---

## ⚠️ Important Notes

* API keys are NOT included in this repository
* You must configure credentials manually in n8n

---

## 📸 Screenshots (Optional)

*Add your workflow screenshots here*

---

## 🌟 Use Cases

* Content tagging systems
* Form automation
* AI-powered data processing
* Lead filtering systems

---

## 👨‍💻 Author

**Sifat221**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
