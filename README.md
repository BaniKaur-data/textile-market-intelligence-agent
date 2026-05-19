# 🧠 Textile Market Intelligence Agent

<p align="center">

<img src="https://img.shields.io/badge/LangGraph-AI%20Workflow-blue?style=for-the-badge" />

<img src="https://img.shields.io/badge/Groq-Llama%203.3%2070B-orange?style=for-the-badge" />

<img src="https://img.shields.io/badge/Tavily-Web%20Search-green?style=for-the-badge" />

<img src="https://img.shields.io/badge/Python-3.11-yellow?style=for-the-badge" />

<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />

</p>

---

# 🚀 Overview

An AI-powered **competitive intelligence agent** built using **LangGraph**, **Groq LLM**, and **Tavily Search** for the textile and bedding industry.

The system automatically:
- researches competitors
- extracts textile product specifications
- analyzes market gaps
- generates strategic insights
- creates executive battlecard reports

Designed specifically for:
- pillow manufacturers
- textile sourcing teams
- bedding brands
- product research teams

---

# 🧩 AI Workflow Architecture

```text
Competitor Research
        ↓
Product Intelligence Extraction
        ↓
Strategy Recommendation Engine
        ↓
Executive Battlecard Report
```

---

# ⚡ Features

✅ Competitor discovery using AI  
✅ Textile specification extraction  
✅ Packaging analysis  
✅ Fabric composition intelligence  
✅ Thread count / GSM analysis  
✅ AI-generated market strategy  
✅ Executive battlecard generation  
✅ Multi-node LangGraph workflow  
✅ Real-world textile industry use case  

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| LangGraph | Multi-step AI workflow orchestration |
| LangChain | LLM framework |
| Groq (Llama 3.3 70B) | High-speed inference |
| Tavily API | AI web search |
| Python | Core development |
| Google Colab | Development environment |

---

# 📊 Example Output

## Workflow

![Workflow](workflow.png)

---

## AI Battlecard Report

![Battlecard](battlecard.png)

---

# 💼 Real Business Use Case

This project simulates how textile companies perform:
- competitor market research
- textile specification comparison
- sourcing intelligence
- premium product positioning
- packaging strategy analysis

Example products:
- Bamboo Pillow Covers
- Memory Foam Pillows
- Charcoal Pillows
- Designer Cushions
- Bamboo Bedding

---

# 🧠 LangGraph Nodes

## 1️⃣ Competitor Research Node
Finds established competitors using Tavily AI search.

## 2️⃣ Product Intelligence Node
Extracts:
- GSM
- Thread Count
- Fabric Composition
- Packaging Type
- Filling Material
- Pack Size

## 3️⃣ Strategy Recommendation Node
Generates:
- market gaps
- premium opportunities
- packaging recommendations
- positioning strategies

## 4️⃣ Battlecard Generation Node
Creates professional executive reports in markdown format.

---

# ▶️ How To Run

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/textile-market-intelligence-agent.git
```

---

## 2. Open Notebook

Open in:

- Google Colab
- Jupyter Notebook

---

## 3. Install Dependencies

```python
!pip install -U langgraph langchain langchain-groq tavily-python pandas
```

---

## 4. Add API Keys

```python
import os

os.environ["GROQ_API_KEY"] = "YOUR_GROQ_API_KEY"

os.environ["TAVILY_API_KEY"] = "YOUR_TAVILY_API_KEY"
```

---

## 5. Run Workflow

```python
result = workflow.invoke({

    "product":
    "Bamboo Pillow Cover"

})

print(result["battlecard_report"])


---

# 📈 Sample Intelligence Fields

| Field | Description |
|---|---|
| GSM | Fabric weight analysis |
| Thread Count | Textile quality indicator |
| Fabric Composition | Bamboo / Cotton / Blends |
| Filling Type | Memory Foam / Polyester / Latex |
| Packaging Type | Vacuum / Woven Bag / Box |
| Pack Size | Single / Set of 2 / Bulk |

---


# 🔮 Future Improvements

- Streamlit dashboard
- Pricing intelligence
- Supplier intelligence


---

# 👨‍💻 Author

### Bani
AI/ML Engineer

---

