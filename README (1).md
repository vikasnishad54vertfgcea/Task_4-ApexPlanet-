# 📊 Data Storytelling & Statistical Validation
### Internship Project — Task 4 of 4 | 16-Day Program

> **Analyst:** Vikas Navik  
> **GitHub:** [github.com/vikasnishad54vertfgcea](https://github.com/vikasnishad54vertfgcea)  
> **LinkedIn:** [linkedin.com/in/vikas-navik-a00029313](https://www.linkedin.com/in/vikas-navik-a00029313)

---

## 📁 Repository Structure

```
Task-4/
│
├── Superstore_Task4_FINAL.pptx   ← 7-slide professional presentation
├── hypothesis_testing.ipynb       ← Jupyter Notebook (real data analysis)
├── dataset.csv                    ← Superstore Sales Dataset (9,994 orders)
└── README.md                      ← This file
```

---

## 🎯 Objective

Synthesize all analysis from Parts 1–3 into a compelling business narrative and validate key findings using statistical methods (T-Test, Chi-Squared, Confidence Intervals).

---

## 📖 Dataset — Superstore Sales

| Property | Value |
|----------|-------|
| Source | Superstore Sales Dataset |
| Total Orders | 9,994 |
| Total Columns | 21 |
| Time Period | 2014 – 2017 |
| Categories | Furniture, Office Supplies, Technology |
| Regions | East, West, Central, South |
| Segments | Consumer, Corporate, Home Office |

---

## 📈 Key Business Metrics (Real Data)

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | $2,297,201 |
| 💹 Total Profit | $286,397 |
| 📊 Profit Margin | 12.5% |
| 📦 Total Orders | 9,994 |
| 📈 Revenue Growth | +51.4% (2014 → 2017) |
| ⚠️ Loss Orders | 18.7% of all orders |

---

## 🔬 Hypothesis Testing — Results

### Business Hypothesis
> **H₀:** Discounts do NOT significantly reduce profit per order  
> **H₁:** Discounts significantly reduce profit — high discounts destroy margins

### Test Method
- **Primary Test:** Independent 2-Sample Welch T-Test
- **Secondary Test:** Chi-Squared Test for proportions
- **Groups:**
  - Group A (Control) → Orders with NO discount
  - Group B (Treatment) → Orders WITH discount

### Results

| Metric | Value |
|--------|-------|
| Avg Profit — No Discount | **$66.90** per order |
| Avg Profit — With Discount | **-$6.66** per order (LOSS) |
| **p-value** | **~0.000000** |
| 95% Confidence Interval | [$64.40, $82.72] |
| Chi-Squared p-value | < 0.05 ✅ |
| High-discount total losses | **$135,376** |

### ✅ Verdict: REJECT H₀

> Discounts are a **statistically proven destroyer of profit** at 99.99% confidence.  
> High-discount orders (>20%) alone generated **$135,376 in losses**.

---

## 🗺️ Regional & Category Findings

### Revenue by Region
| Region | Revenue | Profit |
|--------|---------|--------|
| 🥇 West | $725,458 | $108,418 |
| 🥈 East | $678,781 | $91,523 |
| 🥉 Central | $501,240 | $39,706 |
| South | $391,722 | $46,749 |

### Revenue by Category
| Category | Revenue | Profit Margin |
|----------|---------|---------------|
| 💻 Technology | $836,154 | **17.4%** ✅ |
| 🪑 Furniture | $742,000 | **2.5%** ⚠️ |
| 📎 Office Supplies | $719,047 | **17.0%** ✅ |

---

## 📊 Presentation Structure

| Slide | Title | Content |
|-------|-------|---------|
| 1 | Title Slide | Dataset overview + 3 KPIs |
| 2 | Executive Summary | Business story + 4 KPI cards |
| 3 | Sales Trend Analysis | Year-wise revenue & profit charts |
| 4 | Regional & Category Intelligence | Region bar + Category + Segment pie |
| 5 | Hypothesis Testing | T-Test, p-value, CI, Verdict |
| 6 | Conclusions & Call to Action | 5 findings + 4 strategic actions |
| 7 | Closing Slide | Contact + Links |

---

## 🚀 How to Run the Notebook

```bash
# Step 1 — Install dependencies
pip install jupyter notebook scipy numpy pandas matplotlib

# Step 2 — Clone the repo
git clone https://github.com/vikasnishad54vertfgcea/data-analytics-internship.git
cd data-analytics-internship/Task-4

# Step 3 — Launch Jupyter
jupyter notebook

# Step 4 — Open hypothesis_testing.ipynb → Run All Cells
```

> ⚠️ Make sure `dataset.csv` is in the same folder as the notebook.

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| Python 3 | Core language |
| Pandas | Data loading & manipulation |
| NumPy | Statistical calculations |
| SciPy | T-Test, Chi-Squared test |
| Matplotlib | Charts & visualizations |
| Jupyter Notebook | Interactive analysis |

---

## ✅ Deliverables

- [x] Professional 7-slide presentation deck (`.pptx`)
- [x] Jupyter Notebook with full statistical analysis (`.ipynb`)
- [x] Real Superstore dataset (`.csv`)
- [x] README documentation
- [ ] LinkedIn Video (7–10 min stakeholder walkthrough)

---

## 📌 Strategic Recommendations

1. **Cap discounts at 20% max** — Higher discounts are proven loss-makers
2. **Invest more in West Region** — $725K revenue, highest potential
3. **Prioritize Technology** — Best margin at 17.4%
4. **Fix Furniture strategy** — Only 2.5% margin, needs immediate review
5. **Target Corporate segment** — Highest average order value

---

*Internship Project · Task 4 of 4 · Data Storytelling & Statistical Validation*
