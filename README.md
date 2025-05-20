# 📊 Sweetviz Data Analysis Report

Welcome to the exploratory data analysis (EDA) report generated using **Sweetviz**! 🚀  
This repository helps you understand your dataset through automatic, visualized analysis.

---

## 🧠 About Sweetviz

**Sweetviz** is a Python library that generates beautiful, high-density visualizations to help you explore your data faster and smarter.  
It compares datasets, analyzes target variables, and presents everything in a stunning HTML report.

---

## 🧪 How to Generate the Report

```python
import sweetviz as sv
import pandas as pd

# Load your dataset
df = pd.read_csv("your_data.csv")

# Generate and show report
report = sv.analyze(df)
report.show_html("SWEETVIZ_REPORT.html")
