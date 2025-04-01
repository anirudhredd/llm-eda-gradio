# 📊 LLM-Powered Exploratory Data Analysis (EDA)

This project is an AI-powered EDA tool built using **Gradio**, **Pandas**, **Matplotlib**, and **Seaborn**, with **Mistral-7B** via **Ollama** generating natural language insights on your datasets. Just upload any CSV file and get automated EDA reports + smart visualizations + AI insights — all in one sleek web app.

## 🚀 Features

- 🧠 **AI Insights**: Uses Mistral-7B to generate human-like summaries based on your dataset.
- 📈 **Data Visualizations**: Auto-generates histograms, distributions, and correlation heatmaps.
- 🧹 **Data Cleaning**: Fills missing values smartly (median/mode).
- 💻 **No-Code UI**: Built with Gradio for a plug-and-play experience.

## 🛠️ Tech Stack

- `Gradio` - Web app interface
- `Pandas` - Data wrangling
- `Seaborn & Matplotlib` - Visualizations
- `Ollama + Mistral-7B` - LLM insights
- `Python` - The glue behind it all

## 📦 Installation

### 1. Install Ollama (if not already)
Head to: https://ollama.com and follow install instructions.

Then pull the model:
```bash
ollama pull mistral
