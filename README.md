# Kombajn BI - AI-Powered Business Intelligence Platform 🤖📊

An end-to-end Business Intelligence and automated reporting platform that transforms raw data into production-ready PDF analytical insights using local LLMs and ultra-fast data processing. Built specifically for high-performance data pipeline automation.

## 🚀 Key Features

*   **Local AI Analytical Agent:** Integrated with local LLMs (Llama3 via Ollama) to automatically interpret business data, find trends, and write professional executive summaries.
*   **High-Performance Backend:** Powered by **DuckDB** and **Pandas** for lightning-fast SQL queries and robust structured data manipulation on local machines.
*   **Automated Production-Ready PDF Generation:** Generates comprehensive, styled PDF reports complete with business metadata, data-quality/missing-value checks, and legal compliance clauses.
*   **Modern Interactive UI:** Built with **Streamlit** for seamless, intuitive data uploads and real-time report visualization.

## 🛠️ Tech Stack

*   **Language:** Python 3.11+
*   **Data Processing:** DuckDB, Pandas, NumPy
*   **AI / LLM:** Ollama (Llama3), LangChain / AI Agents architecture
*   **Frontend / UI:** Streamlit
*   **Reporting:** ReportLab (Structured PDF Generation)

## 📦 Project Structure

```text
├── kod_pokazowy.py              # Main Streamlit application & UI
├── core/
│   ├── database.py     # DuckDB connection & SQL query engine
│   ├── ai_agent.py     # Ollama/Llama3 integration & prompt engineering
│   └── reporter.py     # PDF generation engine with styles & metadata
├── data/               # Local data cache and sample files
└── requirements.txt    # Project dependencies
