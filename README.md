# Decision Intelligence System using Simulation + LLM

A **production-style Decision Intelligence system** that combines Monte Carlo simulation, causal features, and a Large Language Model (LLM) to support **data-driven business decisions** in e-commerce operations.

This project is intentionally designed beyond beginner tutorials and reflects how real-world ML + analytics systems are structured in industry.

## Business Problem

E-commerce platforms must make decisions under uncertainty, such as:
- Should we offer discounts to a seller?
- Which orders are at high risk of delay?
- How do logistics and payment methods affect outcomes?

Traditional dashboards show *what happened*.
This system helps answer **“what should we do next?”**

## Solution Overview

We build a Decision Intelligence pipeline that:
1. Models uncertainty using **Monte Carlo simulation**
2. Generates counterfactual outcomes for decisions
3. Uses an **LLM** to explain results in natural language
4. Produces **actionable recommendations**, not just predictions

## System Architecture

Raw Data (Olist E-commerce)
↓
Feature Engineering
↓
Simulation Engine
↓
Decision Scoring Layer
↓
LLM Explanation Engine
↓
Business Recommendation

## Dataset

**Olist Brazilian E-Commerce Dataset (Kaggle)**

Files used:
- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_customers_dataset.csv`
- `olist_sellers_dataset.csv`
- `olist_products_dataset.csv`
- `olist_order_payments_dataset.csv`

Source: Kaggle – Olist Brazilian E-Commerce

## Tech Stack

- Python
- Pandas / NumPy
- Scikit-learn
- Monte Carlo Simulation
- OpenAI / LLM API
- Git & GitHub

## Key Concepts Used

- Decision Intelligence
- Simulation-based reasoning
- Counterfactual analysis
- Feature-driven risk modeling
- LLM-powered explanations
- Production ML structure

## 📁 Project Structure

```text
decision-intelligence-llm/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_simulation_model.ipynb
│
├── src/
│   ├── data_pipeline.py
│   ├── simulation_engine.py
│   ├── decision_logic.py
│   └── llm_explainer.py
│
├── outputs/
│   └── reports/
│
├── requirements.txt
└── README.md
```
## How to Run

1. Clone the repository
```bash
git clone https://github.com/farsanamajeed-09/decision-intelligence-llm.git
```

2. Install dependencies
pip install -r requirements.txt

3. Run notebooks in order:
- Data exploration
- Feature engineering
- Simulation modeling

🧪 Example Decision Question
“If we change the payment method mix, how does delivery delay risk change?”
The system:
- Simulates thousands of possible futures
- Scores decision outcomes
- Explains results in plain English using an LLM

## Output
- Risk scores per decision
- Scenario comparisons
- LLM-generated explanations for stakeholders

## Why This Project Matters

This project demonstrates:
- Thinking beyond accuracy metrics
- Decision-first ML design
- Handling real-world uncertainty with simulation
- Clear communication between ML systems and human decision-makers

This README alone signals **production ML thinking**.

## Author
Mahabooba P.Msss
