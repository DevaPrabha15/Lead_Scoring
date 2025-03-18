# Lead_Scoring_Case_Study
</br>

## Project Description

The goal of this project is to develop a Leads Conversion Classification System for the online course provider X Education. The objective is to create a predictive model that uses a variety of data gathered throughout the client inquiry stage to assess a lead's likelihood of converting. Targeting an 80%+ conversion rate, the organization wants to increase efficiency by giving high-potential leads priority. Currently, the conversion rate is 30%. Key information like Lead Source, Total Time Spent on Website, and Last Activity are among the 9,000+ records from previous leads that make up the dataset. Data preparation, feature engineering, model construction, assessment, and business insights are all part of this project, which offers practical suggestions to improve lead conversion.

## 🔧 Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Statsmodels  
- **Model Used:** Logistic Regression

## 🔍 Exploratory Data Analysis (EDA)

- **Data Cleaning & Preprocessing:** Handled missing values, outliers, and feature scaling.
- **Feature Engineering:** Created new variables based on existing data.
- **Visualization:** Used Matplotlib and Seaborn to explore trends in lead conversion.

## 🚀 Model Training & Evaluation

- **Train-Test Split:** 70% training, 30% testing.
- **Model Used:** Logistic Regression
- **Evaluation Metrics:**
  - Accuracy Score
  - Precision, Recall
  - ROC Curve

## ⚡ Key Findings & Insights

### Factors that increase the probability of lead conversion:
- **Tags_Closed by Horizzon:** This tag increases the likelihood that a lead will convert.
- **Tags_Lost to EINS:** The likelihood of conversion is relatively high for leads that are indicated as lost to EINS.
- **Tags_Will revert after reading the email:** This type of lead typically has a high conversion rate.
- **Lead_Source_Welingak Website:** This website generates leads with a high conversion rate.

### Factors that indicate a lead will not convert:
- **Lead Quality_Worst:** Leads with quality metioned as worst
- **Lead Quality_Not Sure:** Leads with quality mentioned as Not Sure

## 🛠 How to Run
**Clone the repository:**
   ```bash
   git clone <https://github.com/DevaPrabha15/Lead_Scoring.git>
```
## 📈 Future Improvements

- Implement advanced models like Random Forest, XGBoost for better accuracy.
- Incorporate real-time lead scoring based on live data.

## 📂 Project Structure  

| File Name                               | Description                                      |
|-----------------------------------------|------------------------------------------------|
| `LEAD SCORING CASE STUDY- SUMMARY.pdf`  | Approach and Conclusion                        |
| `Lead Scoring Case Study.ipynb`         | Coding and findings in Jupyter with Python |
| `LEAD SCORE CASE STUDY.pdf`             | Case study with visualizations and business insights |
| `README.md`                             | Project documentation                          |
| `Assignment Subjective Questions.pdf`   | Solved Questions                               |


## 📢 Credits & References

- **Project by:** Deva Prabha
