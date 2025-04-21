# 🎯 Predictive lead scoring system to boost sales conversions

## 📚 Project Overview

An online education company, offering professional courses, faced **low lead conversion rates (~30%)** despite significant marketing efforts across search engines and websites.

To boost the efficiency of the sales team and maximize conversion rates, we developed a **Sales Lead Scoring System**.  
This system predicts the likelihood of a lead converting into a customer, allowing the sales team to focus their efforts on high-potential prospects.

---

## 🛠️ Problem Statement

- The company collects user information via web forms after marketing campaigns.
- Most leads collected are either unqualified or not genuinely interested.
- The sales team wastes time contacting low-quality leads, leading to poor productivity and resource utilization.
  
**Objective**:  
Develop a predictive model to:

- Assign a **lead score between 0 and 100** to each inquiry.
- Prioritize leads with **higher chances of conversion**.
- Empower the sales team to focus efforts on promising prospects and improve the overall conversion rate.

---

## 📊 Key Variables

| Variable | Description |
|:--------:|:-----------|
| Prospect ID | Unique identifier for each lead |
| Lead Origin | Source from which the lead arrived (e.g., Landing Page, API) |
| Lead Source | Specific marketing channel (e.g., Google, Organic Search) |
| Time Spent on Website | Duration spent by a user on the website |
| Last Activity | Most recent user action (e.g., Email Opened, Chat Conversation) |
| Specialization | Previous industry/domain of the lead |
| Current Occupation | Employment status (e.g., Student, Employed) |
| City | User's city |
| Asymmetrique Scores | Profile evaluation scores assigned during form submission |

---

## 📈 Solution Approach

- **Exploratory Data Analysis (EDA)**: Deep dive into data distributions, missing values, feature importance.
- **Feature Engineering**: 
  - Cleaned categorical variables.
  - Derived meaningful features.
- **Model Building**:
  - Built predictive models (using OLS regression approach initially).
  - Evaluated models with metrics such as accuracy, precision, recall, and ROC-AUC.
- **Lead Scoring System**:
  - Translated model outputs into **lead scores (0-100)**.
  - Higher scores represent a higher probability of conversion.

---

## ⚙️ Tools and Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Metrics Evaluation)
- Statsmodels (for OLS Regression)
- Jupyter Notebook

---

## 📂 Project Structure

```plaintext
sales_lead_scoring/
│
├── sales_enquiries.ipynb          # Complete notebook with EDA, Modeling, and Scoring
├── README.md                      # Project documentation
├── requirements.txt               # (Optional) Libraries required to run the project
```

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/tariquedts/sales_lead_scoring.git
   cd sales_lead_scoring
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the notebook:

   ```bash
   jupyter notebook sales_enquiries.ipynb
   ```

4. Analyze the lead scores and prioritize your sales funnel accordingly.

---

## 🔮 Future Enhancements

- Implement advanced models like XGBoost or LightGBM for improved accuracy.
- Build an API to serve real-time lead scores to sales dashboards.
- Integrate the model into CRM systems (like Salesforce, Hubspot).

---

## 👨‍💻 Author

- [Tarique-Anwar] | [Your LinkedIn] | [[Your GitHub](https://github.com/tariquedts)]

