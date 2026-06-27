#  Telecom Customer Churn Prediction & Analytics

> **Project Quick Facts:**
> *  **Role:** Data Analyst / Data Scientist
> *  **Focus:** Predictive Modeling, Feature Engineering & Business Intelligence
> *  **Status:** Completed Portfolio Project

An end-to-end Machine Learning and Data Analytics project designed to predict customer attrition for a telecommunications provider. This project bridges the gap between algorithmic outputs and **actionable business retention strategies** to minimize company revenue leakage.

---

##  Business Objective & Impact
Customer churn is one of the most critical financial leaks in telecom. The primary objectives of this framework are:
* **Identify At-Risk Customers:** Build a predictive classification pipeline to flag high-probability churn candidates.
* **Isolate Attrition Drivers:** Run deep Exploratory Data Analysis (EDA) to map demographics and billing indicators linked to dissatisfaction.
* **Formulate Retention Frameworks:** Translate machine learning metrics into data-driven business workflows.

---

##  Dataset Landscape
The analysis is executed on the **Telco Customer Churn** dataset containing profiles for **7,043 customers** with 21 features:
* **Target Label:** `Churn` (Yes / No)
* **Key Features:** `tenure` (months active), `MonthlyCharges`, `TotalCharges`, `Contract` types (Month-to-month, One year, Two year), `PaymentMethod`, and tech services.

---

##  Exploratory Data Analysis (EDA) & Insights
Using `Seaborn` and `Matplotlib`, the data was processed and analyzed to pull critical corporate insights:

*  **The Tenure Crisis:** Risk spikes drastically within the **first 1 to 12 months** of onboarding. If a customer crosses the 20-month threshold, loyalty increases exponentially.
*  **The Contract Trap:** Month-to-month subscribers represent the highest vulnerability group, displaying a significantly higher churn rate compared to long-term contract tiers.
*  **Payment Friction:** Customers utilizing **Electronic Check** payment types display a much higher propensity to leave than those using automated credit sweeps.

---

##  Machine Learning Pipeline & Performance
The modeling process applies structural feature preprocessing, including **Label Encoding** for binary categories, **Train-Test Split**, and model evaluation. 

### Model Evaluation Matrix
Based on the experimental execution in the notebook, the classification models achieved strong evaluation baselines:

| Classification Model | Core Strength |
| :--- | :--- |
| **Logistic Regression** | Baseline statistical convergence, fast inference |
| **Decision Tree Classifier** | Strong feature rules mapping, highly interpretable |
| **Random Forest Classifier** |  **Top Performer** (Ensemble variance reduction) |

* **Winner:** The **Random Forest Classifier** provided the most stable operational balance for identifying true churners while keeping false alarms low.

---

##  Tech Stack & Architecture
* **Core Language:** Python 
* **Data Engineering & Manipulation:** Pandas, NumPy
* **Statistical Visualizations:** Seaborn, Matplotlib
* **Predictive Modeling:** Scikit-Learn (Sklearn)
* **Development Environment:** Jupyter Notebook / Google Colab

---

##  Connect With Me
I am an MBA graduate in **Business Analytics & Data Science** dedicated to leveraging machine learning systems to drive real, measurable corporate growth.

*  **GitHub:** [github.com/sdm1999](https://github.com/sdm1999)
*  **LinkedIn:** [Connect with me on LinkedIn](https://www.linkedin.com/in/soumyadip-maity-data)
