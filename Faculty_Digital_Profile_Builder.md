# 🧠 Faculty Digital Profile Builder using Agentic AI

An intelligent, Agentic AI-powered assistant that automates academic faculty profile creation using IBM Watsonx and Retrieval-Augmented Generation (RAG). This tool extracts structured academic information from unstructured documents (CVs, certificates, spreadsheets) and generates formatted profiles compliant with accreditation standards (NAAC/NBA).

---

## 📌 Project Objective

To reduce the manual effort and inconsistency in creating faculty academic profiles by building an AI agent that:
- Extracts relevant data from documents
- Formats it into structured academic profiles
- Supports natural language queries for quick insights

---

## 🛠 Tech Stack

| Component         | Tool/Service                      |
|------------------|-----------------------------------|
| LLM              | IBM Watsonx Granite               |
| Agent Framework  | LangGraph + ReAct                 |
| Knowledge System | Retrieval-Augmented Generation    |
| File Handling    | PyMuPDF, python-docx, Pandas      |
| Deployment       | IBM Cloud Lite (Code Engine)      |
| Interface (UI)   | Streamlit or FastAPI (optional)   |

---

## 🔍 Key Features

- 🧾 Extracts academic details (degrees, FDPs, publications, patents) from faculty documents
- 🗃️ Generates formatted profiles in DOCX/HTML/PDF
- 💬 Handles queries like:
  - "List all FDPs after 2020"
  - "How many publications in 2022?"
- 📦 Integrated with IBM Granite for LLM-backed summarization and response
- 🔁 Uses RAG for retrieving formatting rules and contextual responses

---

## 🚀 How It Works

1. Upload faculty documents (CVs, certificates, spreadsheets)
2. Agent extracts and parses relevant academic information
3. Uses IBM Granite to generate readable, formatted output
4. Queries can be made in natural language to retrieve specific info

---

## 🧪 Sample Input

A `.docx` file containing:

```
Dr. Mounika Chelamsetti
PhD, MTech, BTech
FDPs: AI for Education - IIT Bombay, 2022
Publications: “AI in Education” - IJCA, 2022
Patents: Intelligent Profile Generator - 2023
```

---

## 🖼 Output

- Academic profile generated in formatted structure (NAAC/NBA)
- Screenshots of result page, query interface, and generated profile

---

## 🎓 IBM Certifications

- [x] Getting Started with AI
- [x] Journey to Cloud
- [x] RAG Lab with LangChain

---

## 🧭 Future Scope

- Multilingual profile support
- Real-time data syncing with Scopus/Google Scholar
- ERP integration for institutions
- Student profile generation module

---

## 👤 Author

**Mounika Chelamsetti**  
B.Tech CSE – Artificial Intelligence  
Pragati Engineering College

---

## 📄 License

This project is for academic and educational use. Open to collaborations and extensions.