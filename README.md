🚀 Agentic AI for Business Insights & Decision Support

An AI-powered system that transforms natural language queries into actionable business insights using automated SQL generation and intelligent workflows.

---

📌 Project Overview

This project focuses on building an Agentic AI system that enables users to interact with business data using simple natural language queries.

Instead of writing SQL or using complex tools, users can ask questions like:

«“Which is the best product based on profit in January?”»

The system automatically:

- Understands the query
- Converts it into SQL
- Retrieves data from the database
- Generates clear, human-readable insights

📊 The system acts as a virtual business analyst, making data-driven decision-making accessible to non-technical users.

---

🧠 Key Features

-  Natural Language Query Processing
-  Automated SQL Query Generation
-  Relevance Classification (LLM-based filtering)
-  Real-time Data Retrieval from MySQL
-  Insight Generation using AI models
-  Workflow Automation using n8n
-  Clean & Structured Business Outputs

---

⚙️ System Architecture

The system is built using a multi-step agentic workflow:

User Query 
   ↓
Relevance Classifier (LLM)
   ↓
SQL Generator
   ↓
SQL Validation Layer
   ↓
Database Execution (MySQL)
   ↓
Data Formatting
   ↓
Insight Generation (AI)
   ↓
Final Output

📌 The workflow is implemented using n8n automation platform.

---

🔄 Workflows

🟢 Workflow 1: Data Ingestion Pipeline

- Data collected from Google Drive (CSV)
- Data cleaning & preprocessing (JavaScript)
- Feature engineering:
  - Revenue = Price × Units Sold
  - Profit = Revenue – Cost
  - Margin (%) calculation
- Stored in MySQL database ("sales_data" table)

---

🔵 Workflow 2: AI Decision Support Engine

- User inputs query via chat interface
- LLM-based classifier filters relevant queries
- SQL is generated dynamically
- Query is validated and executed
- Results are converted into human-readable insights

---

🛠️ Tech Stack

- Workflow Automation: n8n
- Database: MySQL
- AI Models: DeepSeek, OpenAI, Ollama
- Programming: JavaScript
- Data Source: Google Drive (CSV dataset)

---

📊 Sample Use Cases

  📈 Best-performing product
  📉 Worst-performing product
  💰 Revenue & profit analysis
  📦 Category-wise performance
  📅 Monthly trend analysis

---

📷 Sample Output

🔹 Current Output (System Generated)

- JSON-like structured response
- Contains escape characters ("\n")
- Less readable for end users

🔹 Improved Output (Planned Enhancement)

User Query:

«Which is the best product based on profit in January?»

AI Response:

«The top-performing product in January based on profit is Notebook A4, generating ₹9000.

Other high-performing products:

1. Notebook A5 – ₹7000
2. Ball Pen Blue – ₹3840
3. Ball Pen Black – ₹3600
4. Pencil HB – ₹3600»

---

🚧 Limitations

  ❌ Difficulty handling ambiguous queries
  ❌ Inconsistency in AI-generated responses
  ❌ Dependence on prompt design
  ❌ Limited predictive analytics capabilities

---

🔮 Future Enhancements

-  ChatGPT-like conversational output formatting
-  Improved prompt engineering for consistency
-  Predictive analytics integration
-  Real-time data pipelines
-  Dashboard & UI integration
-  Multi-database support

---

📁 Project Structure

├── workflows/
│   ├── data_ingestion.json
│   ├── ai_query_engine.json
├── dataset/
│   └── sales_data.csv
├── screenshots/
│   ├── workflow.png
│   ├── sample_output.png
├── README.md

---

📌 Key Highlights

- 💡 Demonstrates real-world application of Agentic AI
- ⚡ Automates complete data analysis pipeline
- 🧠 Combines NLP + SQL + AI insights
- 📊 Designed for non-technical users

---

👥 Team (Mentor - Mr. Santanu Karmakar)

- Somwrik Sinha
- Subhranil Das
- Anushka Jha
- Subham Bose

---

🎓 Internship Details

- Organization: IDEAS – ISI Kolkata
- Project: Agentic AI in Business Insights
- Duration: Jan 2026 – March 2026

---

🔗 GitHub Repository

👉 https://github.com/SomwrikSinha/agentic-ai-business-insights

---

📜 License

This project is for academic and educational purposes.

---

⭐ Final Note

This project demonstrates how Agentic AI can revolutionize business analytics by making data interaction simple, intelligent, and accessible.

---
