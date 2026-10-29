# 💻 Computer Prices Analysis

Machine Learning mid-term project: analysing **100,000 computers** (desktops and laptops) to understand what drives price, which computers are overpriced or underpriced, and how price segments (Low / Medium / High) can be predicted from specs.

🔗 **Live dashboard:** `https://YOUR-USERNAME.github.io/computer-prices-analysis/`

## 📌 Business Problems

| # | Problem | Model |
|---|---------|-------|
| 1 | Pricing strategy: what drives computer price? | Linear Regression, Random Forest |
| 2 | Find overpriced and underpriced computers | Linear Regression (actual vs predicted price) |
| 3 | Market segments: Low / Medium / High price | Decision Tree (classification) |

## 📊 Key Results

- **Problem 1:** Linear Regression (R² ≈ 0.79, MAE ≈ $201) slightly beat Random Forest (R² ≈ 0.77, MAE ≈ $208). RAM is the most important feature, followed by CPU and GPU tier.
- **Problem 2:** The gap between actual and predicted price flags computers that cost more or less than their specs justify.
- **Problem 3:** The Decision Tree places a computer in the correct price segment about **72%** of the time using specs only (random guessing = 33%).

## 🗂️ Project Files

| File | Description |
|------|-------------|
| `Mid_Term_Computer_Final_Simple.ipynb` | Main notebook: EDA, data prep, models, conclusions |
| `computer_prices_all.csv` | Dataset (100,000 rows, 34 columns) |
| `index.html` | Interactive "Computer Value Check" dashboard |
| `requirements.txt` | Python libraries needed |

## 🚀 How to Run

```bash
git clone https://github.com/daniairfan1812/computer-prices-analysis.git
cd computer-prices-analysis
pip install -r requirements.txt
jupyter notebook Mid_Term_Computer_Final_Simple.ipynb
```

## 🛠️ Tools

Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook, HTML/Chart.js

## 👤 Author

**DANIA IRFAN** · Business Data Analytics, COMSATS University Islamabad
[LinkedIn](https://linkedin.com/in/daniairfan) · [GitHub](https://github.com/daniairfan1812)
