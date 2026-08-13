# n8n-workflow-
# 🤖 AI IT Support Assistant

This project is an **AI-powered IT Support Assistant** built using **n8n, OpenAI, and Supabase**.

I developed this project as part of my work with the **Saudi Data & AI Authority (SDAIA)**, where I explored how AI and RAG can be used to build a simple IT support assistant.

🔗 **SDAIA:** [Saudi Data & AI Authority (SDAIA)](https://sdaia.gov.sa/ar/default.aspx?utm_source=chatgpt.com)

## 💡 About the Project

The idea is to create a chatbot that can answer IT support questions using information stored in a custom knowledge base.

Instead of depending only on the AI model's general knowledge, the assistant can search the stored IT support documents and use the relevant information to generate a better answer.

## ⚙️ How It Works

```text
User
  ↓
n8n Chat
  ↓
AI Agent
  ↓
Search IT Knowledge Base
  ↓
Supabase Vector Store
  ↓
OpenAI
  ↓
AI Response
```

The workflow also includes **conversation memory**, allowing the assistant to keep track of the conversation context.

## 🛠️ Technologies Used

* **n8n** – Workflow automation
* **OpenAI GPT-5 Mini** – AI model
* **OpenAI Embeddings** – Creating document embeddings
* **Supabase** – Vector database
* **RAG** – Retrieving relevant information from the knowledge base

## 📚 What I Learned

Through this project, I learned how to:

* Build an AI workflow using n8n
* Work with AI Agents
* Understand the basics of RAG
* Store and retrieve information using a vector database
* Use embeddings for semantic search
* Connect different AI services together
* Add memory to an AI chatbot

## 🚀 Future Improvements

Some improvements I would like to add in the future:

* Add more IT support documents
* Improve the document retrieval process
* Add more tools to the AI Agent
* Improve the chatbot interface
* Add authentication and user management

## 🤝 Project Collaboration

This project was developed as part of my work with:

**Saudi Data & AI Authority (SDAIA)**
🔗 [sdaia.gov.sa](https://sdaia.gov.sa/ar/default.aspx?utm_source=chatgpt.com)

---
