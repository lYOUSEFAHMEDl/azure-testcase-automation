# 🚀 Azure DevOps Test Case Automation with Postman + AI

This project automates the process of generating and uploading test cases to **Azure DevOps** using **AI-generated prompts**, **Postman**, and the **Azure DevOps REST API**.

## 🔍 Overview

In many QA teams, writing test cases manually from user stories takes time and effort. This workflow reduces that manual load and speeds up the process using:

- ✅ **Azure DevOps API** to fetch User Stories
- 🤖 **AI (ChatGPT or any LLM)** to generate Test Cases from Acceptance Criteria
- 🛠️ **Postman Collection** to upload the generated Test Cases automatically

## 📁 Project Structure
📦 azure-testcase-automation/
├── 🧠 AI-Prompt-for-TestCase-Generation.txt
├── 🧪 AzureDevOps-TestCase-Automation.postman_collection.json
├── 📄 sample-testcases.json
├── 📝 README.md
└── .gitignore


## ⚙️ How It Works

### Step 1 – Fetch User Story
Use Azure DevOps API to get the `Description` and `Acceptance Criteria` by work item ID.

### Step 2 – Generate Test Cases with AI
Use the prompt in `AI-Prompt-for-TestCase-Generation.txt` to generate test cases in JSON format via ChatGPT or another LLM.

### Step 3 – Review and Edit
You stay in the loop—review and fine-tune the generated test cases before uploading.

### Step 4 – Upload to Azure DevOps
Use the provided Postman Collection (`AzureDevOps-TestCase-Automation.postman_collection.json`) to upload test cases via the Azure API, linked to the original User Story.

## 🧩 Requirements

- Postman installed
- Azure DevOps account with a Personal Access Token (PAT)
- Basic understanding of REST APIs

## 💡 Why Use This?

- ⏱️ Save time and reduce repetitive work
- ✅ Improve consistency in test case creation
- 🤖 Combine the power of AI with human QA insight
- 🔁 Reuse the workflow across sprints and teams




