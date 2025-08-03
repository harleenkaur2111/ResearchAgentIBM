# 🔬 IBM Watsonx Research Agent

An intelligent academic assistant built using IBM Watsonx.ai and the Granite 3-3-8B-Instruct foundation model.  
This agent automates common research workflows like summarizing topics, finding research gaps, and suggesting citations.

---

## 📌 Features

- ✅ Understands academic queries using a custom prompt
- 📚 Summarizes complex research topics
- 🕵️ Retrieves real academic papers from the web using custom tools
- 📑 Generates IEEE-style citations (on request)
- 🛠️ Modular tools: Google, Wikipedia, and DuckDuckGo academic search

---

## 🛠️ Technologies Used

| Component         | Technology Used                      |
|------------------|--------------------------------------|
| Agent Framework  | IBM Watsonx.ai + LangChain           |
| LLM Model        | Granite-3-3-8b-instruct (Lite Plan)  |
| Tool Execution   | Python (Custom Tools)                |
| Hosting          | IBM Watsonx Project + Runtime        |

---

## ⚙️ How It Works

1. **User inputs a research question** through the agent interface.
2. **Agent decides whether to use tools** (Google, Wikipedia, DuckDuckGo).
3. **Relevant data is fetched** (e.g., top research paper links).
4. **Prompt is constructed** using user input + context.
5. **Granite LLM generates an answer** in academic format.

---

## 🧪 Test Questions You Can Try

- *“Summarize current research on quantum entanglement.”*  
- *“What are some research gaps in bioinformatics?”*  
- *“Suggest related questions to AI in medical diagnosis.”*  
- *“Give me IEEE citations for AI in climate modeling.”*

---

## 🚧 Known Limitations

- 🧠 DocumentSearch tool not supported in Lite Plan
- 📥 PDF summarizer tool under development
- 🚀 Lite plan restricts deployment quota (1 per month)

---

## 💡 Future Enhancements

- PDF upload and summarization tool  
- Ingestion of user-uploaded research papers  
- Chat memory for long-form research conversations  
- Frontend UI (Flask/React) for easier access

---

## 🧾 License

This project is part of the SB4 Academia program. For educational use only.

---




