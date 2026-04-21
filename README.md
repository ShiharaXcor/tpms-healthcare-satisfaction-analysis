# TPMS Assignment: Healthcare Environment & Patient Satisfaction

**Statement to test:**  
*Healthcare environments that feel welcoming improve patient satisfaction.*

This project performs a full statistical analysis (descriptive, inferential, predictive) on the **2020 US Hospital Customer Satisfaction dataset** from Kaggle. The goal is to prove whether the statement is true or false using hypothesis testing (H₀ vs H₁) and regression modelling.

---

## 📁 Project Structure
tpms-healthcare-satisfaction-analysis/
│
├── data/ # Place the raw CSV here
│ └── hospital_satisfaction_2020.csv
│
├── notebooks/ # Jupyter notebooks (ordered)
│ ├── 01_data_cleaning.ipynb
│ ├── 02_descriptive_analytics.ipynb
│ ├── 03_inferential_analytics.ipynb
│ └── 04_predictive_analytics.ipynb
│
├── reports/ # Auto‑generated outputs
│ └── figures/ # All plots saved as PNG
│
├── requirements.txt # Python dependencies
└── README.md

text

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tpms-healthcare-satisfaction-analysis.git
   cd tpms-healthcare-satisfaction-analysis
Create a virtual environment (optional but recommended)

bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
Install dependencies

bash
pip install -r requirements.txt
Add the dataset
Download the 2020 CSV from Kaggle and place it inside the data/ folder as hospital_satisfaction_2020.csv.

Run the notebooks
Open VS Code, navigate to the notebooks/ folder, and execute cells in order:




01_data_cleaning.ipynb

02_descriptive_analytics.ipynb

03_inferential_analytics.ipynb

04_predictive_analytics.ipynb




### Analysis Phases
Phase	Description
Data Cleaning	Handle missing values, encode categorical variables, select relevant columns.
Descriptive Analytics	Summary stats, correlation matrix, histograms, boxplots, heatmaps.
Inferential Analytics	t‑tests / ANOVA / Mann‑Whitney U to test H₀: no relationship vs H₁: positive relationship.
Predictive Analytics	Multiple linear regression (OLS) to quantify how much “welcoming” explains satisfaction.


###  Key Results
(After running the notebooks, fill in your actual findings)

Correlation between welcoming score and satisfaction: r = ...

t‑test p‑value: ... → Reject H₀ / Fail to reject H₀

Regression R²: ...

Final conclusion: The statement is supported / not supported by the 2020 data.



### Dependencies
See requirements.txt. Main libraries:

pandas, numpy

scipy, statsmodels

scikit‑learn

matplotlib, seaborn

jupyter



### References

Kaggle dataset: https://www.kaggle.com/datasets/kaggleprollc/healthcare-patient-satisfaction-data-collection

HDSC Summer’22 Project Presentation

Python libraries documentation

### License

This project is for educational purposes only – part of a university TPMS assignment.


Just copy the entire block above and paste it into your `README.md` file. Replace `shiharaXcore` with your actual GitHub username if needed, and fill in the group members and results after you finish the analysis.