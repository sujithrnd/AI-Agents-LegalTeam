# ⚖️ AI Legal Team Agents

## 🚀 Overview
AI-powered **Legal Agents** designed to assist with **contract analysis, legal research, risk assessment, and compliance checks**.  
This system processes **legal documents (PDFs)** using advanced AI models and knowledge bases, providing structured insights and recommendations.

🔹 Upload legal documents  
🔹 Get insights from multiple AI agents  
🔹 Perform contract analysis, legal research & risk assessment  
🔹 Receive structured legal reports  

---
**AI Agent Work Flow**
<img width="1217" height="558" alt="legal_flow" src="https://github.com/user-attachments/assets/05c1ec43-e07f-4b22-987e-7516632c47f6" />

** User Intreface**

<img width="1916" height="1022" alt="legal1" src="https://github.com/user-attachments/assets/cfa223c0-16f9-481a-ab57-00f3deb36d57" />
<img width="1912" height="1026" alt="legal3" src="https://github.com/user-attachments/assets/2ccb18b9-bb9e-4e83-8406-4303c2befb72" />
<img width="1917" height="1027" alt="legal2" src="https://github.com/user-attachments/assets/0bdfe7ec-a5b2-4ec3-855b-ce89127e6fbb" />


## 🛠️ Installation Guide

### **1️⃣ Clone the Repository**

```bash
git clone https://github.com/your-repo/legal-ai-agents.git
cd legal-ai-agents

pip install -r requirements.txt

uv venv legal_env --python 3.12

streamlit run legal_team.py

# remove all instaalrtion
pip freeze > to_remove.txt && pip uninstall -r to_remove.txt -y


####install uv
# Open Windows Power Shell and Run the below command
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

# Using winget
winget install --id=astral-sh.uv  -e

# Using scoop
scoop install main/uv



```
# Core Framework & UI
agno
streamlit
python-dotenv

# AI Model Providers
google-genai
openai          # Required for xAI (Grok) as it uses the OpenAI-compatible SDK
duckduckgo-search
ddgs

# Knowledge Base & Vector DB
pypdf           # Required by PDFReader
chromadb        # Vector database for storage
