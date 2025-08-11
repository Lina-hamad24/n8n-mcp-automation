# n8n-mcp-automation

This repository contains a modular, automated agent built with **n8n**, **LangChain**, and **Google Gemini**, designed to intelligently interact with Gmail and Google Drive.

The goal of this project is to streamline daily workflows by allowing natural language interaction with your Google Workspace — enabling tasks like searching emails, summarizing documents, or locating files via smart prompts.

---

## 🧠 Features

- **Natural Language Commands**  
  Issue intuitive prompts like “Find today’s emails with attachments” or “Summarize the latest report in Drive”.

- **Gmail Automation**  
  - Search, read, and filter emails based on keywords, dates, or senders.  
  - Retrieve content or metadata from selected messages.

- **Drive Integration**  
  - Locate files using natural language queries.  
  - Fetch and summarize Google Docs or PDFs.

- **Conversational Agent**  
  - Powered by LangChain and Gemini for understanding and executing user intents.  
  - Maintains memory across interactions when connected to an MCP server.

- **Modular & Extendable**  
  - Built in n8n for easy modification.  
  - Can be extended to other platforms (e.g., Slack, Telegram, CRMs, etc.)

---

## ⚙️ Technologies Used

| Component        | Purpose                              |
|------------------|--------------------------------------|
| **n8n**          | Workflow automation engine           |
| **LangChain**    | Agent logic and memory               |
| **Google Gemini**| Natural language understanding       |
| **Gmail API**    | Read and search emails               |
| **Google Drive API** | Access and process Drive files |
| **MCP Server (optional)** | External memory/agent hub  |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Lina-hamad24/n8n-mcp-automation.git
cd n8n-mcp-automation

https://github.com/user-attachments/assets/ee160128-6d29-4229-8a9d-d8a6bc7fa8d9
