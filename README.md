# 🤖 LLM Benchmark Performance Dashboard

## 📌 Project Overview

This project analyzes **Large Language Model (LLM) benchmark performance** using **Power BI**.
The dashboard compares different AI models across **benchmark scores, speed, latency, pricing tiers, and organizational contributions**.

The goal of this project is to provide **insights into the performance, efficiency, and cost-effectiveness of modern LLMs**.

---

# 🖥️ Dashboard Preview

### Key Metrics

* **24 Total Models**
* **11 AI Organizations**
* **Latest Release Year: 2025**

### Key Visualizations

* Models by Organization
* Model Architecture Distribution
* Models by Country
* Model Releases by Year

---

### Benchmarks Used

| Benchmark        | Description                        |
| ---------------- | ---------------------------------- |
| **HumanEval**    | Code generation benchmark          |
| **AIME**         | Mathematical reasoning benchmark   |
| **GPQA Diamond** | Graduate-level reasoning benchmark |

### Key Metrics

* **Best HumanEval Score:** 97.5
* **Best AIME Score:** 100
* **Best GPQA Score:** 94.3

### Key Insights

* Claude and GPT models dominate **benchmark performance**.
* Newer models consistently outperform older ones.

---
### Key Metrics

* **Fastest Model Speed:** 387 tokens/sec
* **Lowest Latency:** 0.18 seconds
* **Best Value Model Score:** 9.02K

### Key Analysis

* Speed comparison across models
* Latency by context size
* Price tier distribution
* Performance per dollar comparison

---

# 🗄️ Data Model (Star Schema)

The dashboard uses a **multi-table relational data model connected using `Model_ID`**.

### Tables Used

| Table                  | Description                                      |
| ---------------------- | ------------------------------------------------ |
| `Model_Info_Dim`       | Model details (name, organization, architecture) |
| `Benchmark_Scores_Dim` | Benchmark scores like HumanEval, GPQA            |
| `Model_Ranking_Fact`   | Ranking metrics and evaluation                   |
| `Pricing_Speed_Dim`    | Speed, latency, and pricing information          |
| `llm_benchmark_comp`   | Overall benchmark comparison dataset             |

### Relationship

All tables are connected using:

```
Model_ID
```

This enables **accurate cross-table analysis and filtering across dashboards**.

---

# 📊 Key Insights

### 🏢 Organizations

* Major AI labs such as **OpenAI, Anthropic, DeepMind, and Meta** dominate LLM development.

### 🧠 Benchmark Performance

* Claude and GPT series show **top performance across multiple benchmarks**.

### ⚡ Efficiency

* Some models prioritize **speed**, while others optimize for **accuracy and reasoning**.

### 💰 Cost Efficiency

* Certain models deliver **better performance per dollar**, making them more cost-effective.

---

# 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling (Star Schema)**
* **Interactive Data Visualization**

---

# ⚙️ Dashboard Features

✔ Multi-page interactive dashboard
✔ Cross-filtering between visuals
✔ Star schema data model
✔ Performance benchmarking comparison
✔ Efficiency and cost analysis

---

# 🚀 How to Use

1. Clone or download the repository
2. Open the `.pbix` file using **Power BI Desktop**
3. Refresh the dataset if necessary
4. Explore the dashboards using filters

---

# 📈 Future Improvements

* Add **time-series analysis of model evolution**
* Integrate **LLM leaderboard API**
* Deploy dashboard in **Power BI Service**
* Add **AI model cost prediction**

---

# 👨‍💻 Author

**Sahara M**
B.Tech – Artificial Intelligence & Data Science
