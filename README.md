# Eniac-A-B-Testing-Analysis-Optimizing-Click-Through-Rate
![Banner](banner.png) 

## 🧠 Overview
This project presents the complete analysis of an A/B test conducted for **Eniac**, a tech e-commerce company aiming to increase the **Click-Through Rate (CTR)** of its homepage “SHOP NOW” button. The team tested four different design variants to evaluate which performs best, using rigorous statistical methods and business metrics.

---

## 🎯 Objective

Determine if any visual or textual change to the homepage call-to-action increases engagement (CTR), while also evaluating impact on:
- Drop-off rate
- Homepage-return rate

---

## 📁 Files Included

- `Eniac_AB_test.ipynb` – Full Python notebook for:
  - Data loading
  - Metric analysis
  - Chi-squared and post-hoc testing
  - Interpretation & conclusion
- `Eniac AB Testing case study.pdf` – Business case and experiment context
- CSV datasets:
  - `eniac_A.csv`
  - `eniac_B.csv`
  - `eniac_C.csv`
  - `eniac_D.csv`
- `requirements.txt` – Python environment setup
- `.gitignore` – To clean unneeded files
- `LICENSE` – MIT License

---

## 🧪 Experiment Setup

### 🧱 Variants Tested

| Version | Description                            |
|---------|-----------------------------------------|
| A       | Original White "SHOP NOW"              |
| B       | Red "SHOP NOW"                         |
| C       | White "SEE DEALS"                      |
| D       | Red "SEE DEALS"                        |

### 📊 Metrics

- **Click-Through Rate (CTR)**: Clicks / Total Visits
- **Drop-Off Rate**: Users who left mid-conversion
- **Homepage-Return Rate**: Users returning after clicking

---

## 📊 Statistical Methodology

1. **CTR Calculation**
2. **Chi-Squared Test for Independence**

   ```python
   from scipy.stats import chi2_contingency
   chi2_contingency(contingency_table)
3. Post-Hoc Testing (Bonferroni Adjustment)
Adjusted significance level for multiple comparisons.
corrected_alpha = 0.05 / number_of_comparisons

## ✅ Results & Final Decision
Version A performed the best in CTR and user behavior metrics.

Versions with red buttons (B & D) consistently underperformed.

Statistical significance confirmed via chi-squared and post-hoc testing.

Drop-off and return rates reinforced the choice of keeping Version A.

## 🔍 Final Recommendation
✔️ Keep Version A (original white "SHOP NOW" button)
❌ Avoid red-colored variations for this CTA based on tested metrics

## 💡 Business Impact
Data-driven UX design decisions

Increased top-of-funnel conversion

Reduced cost by avoiding ineffective redesigns

Dr. Carlos Montefusco Pereira\
Data Analyst | Experimental Design | A/B Testing\
[linkedin.com/in/carlos-montefusco-pereira-dr-he-him-ab663221/] | [cmontefusco@gmail.com]

📄 License
This project is licensed under the MIT License.
