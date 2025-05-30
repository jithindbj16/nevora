

```markdown
# 📦 Nevora
---

# Nevora: Transform Warranty and Reliability Data with Ease

Nevora helps you seamlessly convert sales and returns data into Nevada chart format — the essential starting point for warranty analysis, survival modeling, and reliability forecasting.  
Built for engineers, analysts, and data scientists who want clean, analysis-ready data without the manual grind.

---
[pyproject.toml](pyproject.toml)
## 🚀 Key Features
- 📊 Nevada Chart Converter: Instantly pivot raw sales/returns into a professional Nevada matrix.
- ⏳ Auto Time Bucketing: Monthly, quarterly, yearly — you choose.
- 🔍 Ready for Survival Analysis: Your first step to reliability modeling.
- 🛠️ Future Enhancements: Plot Nevada charts, fit survival curves, reliability forecasts.
- 🧹 Clean API: Simple, minimalistic, and powerful.

---

## 📥 Installation

```bash
pip install nevora
```

---

## ⚡ Quickstart

```python
import pandas as pd
from nevora import NevadaConverter

# Load your sales/returns data
df = pd.read_csv('sales_returns.csv')

# Convert to Nevada format
converter = NevadaConverter(time_bucket='M')  # 'M' = monthly bucketing
nevada_matrix = converter.to_nevada_format(df)

# View the output
print(nevada_matrix)
```

> 🎯 Tip: You can use any custom time bucket like `'Q'` (quarterly), `'Y'` (yearly) based on your needs.

---

## 📈 Upcoming Roadmap
- 🎨 Plot beautiful Nevada charts automatically
- ⏱️ Fit Kaplan-Meier and Weibull survival models
- 🔮 Forecast warranty returns and reliability metrics
- 🌎 Export datasets for external tools like ReliaSoft and Minitab

---

## 💬 Why Nevora?
Warranty analysis and reliability modeling start with good data.  
Nevora automates the most painful and error-prone step, letting you focus on insights — not spreadsheet wrangling.

---

## 🤝 Contributing
Pull requests, feature suggestions, and issue reports are warmly welcome.  
Let's make warranty and reliability analysis effortless for everyone.

---

## 📄 License
MIT License
