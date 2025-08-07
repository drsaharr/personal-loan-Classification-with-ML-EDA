# personal-loan-Classification-with-ML-EDA
Machine learning project for prediction personal loan approvals using classification models and ZIP-code based geolocation mapping.
This project is designed to explore the feasibility of predicting whether a loan application will be approved or rejected, based on customer profile data. We perform end-to-end data analysis, feature engineering, and modeling using classical ML algorithms.

Additionally, we use geolocation mapping with folium to visualize the distribution of loan applications based on ZIP codes.



 📁 Dataset

  -Synthetic or anonymized dataset containing:
  - Demographic features (Age, Education, ZIP Code)
  - Financial features (Income, Mortgage, Credit Card Usage)
  - Loan status (Approved/Rejected)

## 📊 EDA Highlights

- Distribution plots for numerical and categorical features  
- Correlation heatmap to identify predictive power  
- Loan approval rate by income and education  
- Outlier detection and handling  
- Feature importance analysis

---

## 🧠 Models Used
logistic Regression 98%
k-Nearest Neighbors 98%
naive bayes 91%

## 📊 Exploratory Data Analysis (EDA)

- Distribution Analysis** – Understanding customer features (e.g., income, age, education)

- target Class Balance** – Check if the dataset is imbalanced

- Correlation Matrix** – Identify multicollinearity

- Boxplots & Histograms** – Detect outliers and skewness

- Feature Engineering** – ZIP code transformation and handling categorical features


  ## 🗺️ Geolocation Mapping (ZIP Codes)



- ZIP Codes are converted to **latitude & longitude** using `pgeocode`

- Created an **interactive map** using `folium` showing application locations

- Each point includes a popup showing:

  - ZIP Code

  - Latitude & Longitude

- Map is saved as `zip_map.html`



## 📂 Dataset Overview

- Features include:

  - Demographic: Age, ZIP Code, Education...

  - Financial: Income, Mortgage, Credit Card Spending...

  - Target Variable: Loan Approval (1 = Approved, 0 = Not Approved)



## 📈 Performance Evaluation



- **Accuracy**

- **Confusion Matrix**

- **Classification Report** (Precision, Recall, F1-Score)

- **Cross-Validation** (if applicable)
