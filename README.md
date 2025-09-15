
# ⚖️ AI Crew Legal Assistant

An **AI-powered Legal Assistant** that helps users understand legal issues in plain English, map them to relevant **Indian Penal Code (IPC)** sections, retrieve legal precedents, and generate formal legal documents.  
The system leverages **multi-agent orchestration (CrewAI)** and **semantic search (LangChain + ChromaDB)** with an interactive **Streamlit UI**.  

---

## ✨ Features
- 📝 **Plain English Explanations** – Simplifies complex legal issues for better understanding.  
- 📜 **IPC Section Mapping** – Identifies and retrieves relevant IPC sections using semantic search.  
- ⚖️ **Legal Precedent Retrieval** – Provides case law references for stronger legal context.  
- 🏛️ **Formal Document Drafting** – Auto-generates structured legal documents.  
- 🤖 **Multi-Agent Workflow** (via CrewAI):  
  - Case Intake Agent  
  - IPC Section Agent  
  - Legal Precedent Agent  
  - Legal Drafter Agent  
- 💻 **Streamlit UI** – Interactive frontend for entering legal problems and viewing results.  
- 🗂️ **Vector Database** – Built with ChromaDB + HuggingFace embeddings for similarity-based IPC retrieval.  
- 🖥️ **CLI Mode** – Run workflows and test with real-world queries without the web app.  

---

## 🛠️ Tech Stack
- **Python**  
- **Streamlit** (UI)  
- **CrewAI** (multi-agent orchestration)  
- **LangChain + ChromaDB** (vector database)  
- **HuggingFace Embeddings** (semantic search)  
- **dotenv** (environment config)  

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/ai-crew-legal-assistant.git
cd ai-crew-legal-assistant
