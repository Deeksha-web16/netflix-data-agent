# 🎬 Netflix Data Intelligence Agent

### **End-to-End Multi-Agent System for Data Cleaning, Analysis & Automated Insights**

A fully autonomous **multi-agent pipeline** that loads, cleans, analyzes, and visualizes the **Netflix Titles Dataset**, generating a polished insights report with observability, memory, and tool-based agent workflows.

This repository demonstrates a production-inspired agent architecture using **custom tools, parallel execution, multi-agent orchestration, and memory systems**.

---

## ⭐ Features

### 🔹 **1. Multi-Agent Architecture**

The system uses a clean, modular workflow:

1. **DataLoader Agent** – loads dataset, validates schema
2. **Cleaning Agent** – sanitizes, normalizes, validates data
3. **Analysis Agent** – computes key metrics & statistics
4. **Visualization Agent** – generates charts (some in parallel)
5. **Insight Agent** – creates a readable insights report

---

## 🔧 Technologies & Concepts Used

* ⚙️ **Custom Tools** (loader, cleaner, analyzer, plotter, reporter)
* 🤝 **Multi-agent orchestration**
* 🔁 **Loop agent** (iterative refinement cycle)
* 📨 **Agent-to-Agent messaging (A2A)**
* 🧠 **Memory Bank (long-term)**
* 💾 **Session Memory (short-term)**
* 📊 **Parallel plotting using ThreadPoolExecutor**
* 🧩 **Context compaction**
* 🕒 **Pause/Resume (long-running simulation)**
* 📁 **Reproducible outputs saved as files**
* 🔍 **Observability** (agent.log, metrics, evaluation JSON)

---

## 📊 Example Outputs

After execution, the system generates:

```
/netflix_agent_outputs/
 ├── insights.txt
 ├── plots/
 ├── agent.log
 ├── session_memory.json
 ├── memory_bank.json
 └── agent_evaluation.json
```

---

## 📥 Dataset

Uses the public Netflix Titles dataset:
**titles.csv** — contains metadata for all Netflix shows & movies.

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/netflix-data-intelligence-agent
cd netflix-data-intelligence-agent
```

Install requirements:

```bash
pip install -r requirements.txt
```

Run the notebook or Python script:

```bash
jupyter notebook
```

Execute cells top-to-bottom.

---

## 🧠 Architecture Overview

The agent pipeline follows this structure:

```
RAW DATA → Loader Agent 
          → Cleaning Agent 
          → Analysis Agent 
          → Visualization Agent (parallel tasks)
          → Insight Generator Agent 
          → Final Reports + Memory + Logs
```

---

## 📈 Why This Project Matters

This demonstrates how **AI agents** can automate real enterprise workflows such as:

* ETL (Extract, Transform, Load)
* BI/Analytics Pipeline
* Automated Reporting
* Memory-enhanced agent reasoning
* Modular & scalable pipelines

Perfect for enterprise use cases involving catalog data, streaming metadata, ecommerce listings, and more.

---

## 📚 Repository Structure

```
📁 project/
 ├── netflix_data_agent.ipynb
 ├── README.md
 ├── requirements.txt
 └── netflix_agent_outputs/  (generated files after run)
```

---

## 👩‍💻 Author

**Deeksha**
Multi-Agent Systems • Data Engineering • AI Automation

---

## 🏷 License

MIT License (recommended for GitHub)

---

✅ **A shorter README for your portfolio**
Just say **“Generate requirements.txt”** or whatever you need!
