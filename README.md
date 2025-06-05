
# 🧠 Multi-Agent LLM System with Groq, OpenAI, Ollama & Phi

This repository showcases multiple implementations of LLM agents using different LLM providers and tools. These agents are capable of performing automated tasks such as stock analysis, financial data fetching, cryptocurrency tracking, e-commerce product search, travel info, and news summarization.

---

## 🔧 Features

- ✅ Stock analysis using Phi agents + yFinance
- ✅ Groq-based LLaMA 3 multi-agent system
- ✅ OpenAI function calling agents
- ✅ Local Ollama agents with Python functions
- ✅ Modular, scalable agent architecture

---

#📁 File Breakdown

| File                        | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `groq_agents.py`           | Multi-agent system using Groq + yFinance for stock data and insights       |
| `openai_agents2.py`        | OpenAI-based agent system with built-in function tools                      |
| `ollama agents.py`         | Uses Ollama local models + custom Python functions                          |
| `llm_multi_agent.py`       | Multi-agent system for news, crypto, e-commerce, travel, sports via Phi     |
| `agents with python functions.py` | Autonomous finance agent for stock info using Phi + Groq + tools       |

---

#⚙️ Setup

1. #Clone the repo

   git clone https://github.com/Rapoluakash/AI-Multi-Agent-Hub-for-Finance-News-E-Commerce-Phi-Agents
  


2. #Install dependencies

   
   pip install -r requirements.txt
  

3. **Set environment variables**

   Create a `.env` file:

   dotenv
   GROQ_API_KEY=your_groq_api_key
   OPENAI_API_KEY=your_openai_api_key
  

#Usage

#Run Groq agents:

```bash
python groq_agents.py
```

### Run OpenAI agents:

bash
python openai_agents2.py


#Run Ollama agents:

bash
python "ollama agents.py"

#Run LLM Multi-Agent (news, crypto, travel, sports):

bash
python llm_multi_agent.py


#Run finance agent (stocks):

bash
python "agents with python functions.py"




#📦 Requirements

* Python 3.8+
* `phi`
* `langchain`
* `yfinance`
* `openai`
* `groq`
* `ollama` (optional, for local models)
* `dotenv`



#📄 License

This project is licensed under the MIT License.



## 🙌 Credits

Built using:

* [Phi](https://github.com/joaomdmoura/phi)
* [Groq API](https://groq.com)
* [OpenAI API](https://platform.openai.com)
* [Ollama](https://ollama.com)
* [YFinance](https://pypi.org/project/yfinance)


