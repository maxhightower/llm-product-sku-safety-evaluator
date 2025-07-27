# 🧪 Ingredient Inspector

A locally hosted app to analyze the ingredients of consumer products for safety, health impact, and legal compliance across regions such as the **EU**, **California (Prop 65)**, **Canada**, and more. It uses a combination of **web scraping**, **LLM-powered evaluation**, and **regulatory datasets** to provide a transparent, research-backed safety report.

---

## 🌟 Features

- 🔍 **Enter a product URL or name** to analyze
- 🧬 **Extract ingredients** via scraping or product page parsing
- 🧠 **Use LLMs or rules** to evaluate the health and environmental impact
- 📜 **Check legality** of ingredients in different regions (e.g., EU bans, Prop 65)
- 📊 **Generate a safety score** with supporting data
- 🖥️ Designed for **local use**, no public hosting required

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/ingredient-inspector.git
cd ingredient-inspector
```

## Install Dependencies
```bash
pip install -r requirements.txt
```

## Run App Locally
```bash
streamlit run app/main.py
```

## Project Structure
ingredient-inspector/
├── app/
│   ├── main.py              # Streamlit UI
│   ├── scraper.py           # Web scraping logic
│   ├── ingredient_extractor.py  # Ingredient parser
│   ├── regulatory_checker.py    # Region-based regulation checks
│   ├── evaluator.py         # LLM or rules-based evaluation
│   └── utils.py             # Shared helpers
├── data/
│   └── regulations/         # CSVs or JSONs for laws & ingredient bans
├── models/
│   └── prompts/             # Prompt templates for LLM evaluation
├── requirements.txt
├── README.md
└── .gitignore



