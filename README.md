<div align="center">

#  Customer Retention & Dynamic Pricing Analysis

### Hospitality Analytics | Machine Learning | Business Intelligence

</div>

---

#  Project Overview

The hospitality industry faces significant revenue loss due to customer cancellations, poor demand forecasting, and inefficient pricing strategies.

This project analyzes hotel booking data using **Python, Exploratory Data Analysis (EDA), Machine Learning, and Power BI** to identify cancellation patterns, optimize pricing strategies, and improve customer retention.

---

#  Executive Problem Statement

In the highly competitive hospitality sector, hotels and travel agencies suffer from:

- High booking cancellation rates
- Revenue leakage
- Unoptimized room pricing
- Poor demand forecasting

Traditional systems lack predictive intelligence to:

- Predict customer cancellations
- Adjust room pricing dynamically based on demand and seasonality

This project provides analytical insights to support:

- Dynamic pricing strategies
- Customer retention campaigns
- Revenue optimization
- Demand forecasting

---

#  Business Objectives

- Reduce customer cancellation rates
- Improve customer retention
- Optimize Revenue Per Available Room (RevPAR)
- Understand seasonal demand trends
- Enable data-driven pricing decisions

---

#  Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| Total Bookings | Total hotel reservations |
| Cancellation Rate | Percentage of cancelled bookings |
| Average Lead Time | Average days before arrival |
| Average ADR | Average Daily Room Rate |
| Revenue Trends | Revenue performance over time |
| Retention Score | Repeat guest contribution |

---

#  Dataset Information

| File | Description |
|------|-------------|
| `Uncleaned hotel_bookings.csv` | Raw hotel booking dataset |
| `cleaned_hotel_bookings.csv` | Processed and cleaned dataset |
| `EDA_hotel_bookings.ipynb` | Exploratory Data Analysis notebook |
| `ML_customer_retention and dynamic pricing.ipynb` | Machine Learning notebook |

---

#  Technologies Used

##  Programming & Analytics
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

##  Dashboard & Visualization
- Power BI

##  Development Environment
- Jupyter Notebook
  

---

#  Data Cleaning Process

The raw dataset contained:

- Missing values
- Duplicate records
- Incorrect data types
- Categorical inconsistencies

##  Cleaning Steps Performed

- Removed duplicates
- Handled missing values
- Converted date columns
- Encoded categorical variables
- Feature engineering
- Outlier handling

##  Example Transformations

```python
df['arrival_date_month'] = pd.to_datetime(
    df['arrival_date_month'],
    format='%B'
).dt.month
```

```python
df = pd.get_dummies(
    df,
    columns=['hotel', 'deposit_type', 'customer_type'],
    drop_first=True
)
```

---

#  Exploratory Data Analysis (EDA)

##  Key Insights

### 🔹 Cancellation Patterns
- Longer lead times resulted in higher cancellation probability
- Certain customer segments showed higher churn
- Non-refundable deposits reduced cancellations

### 🔹 Seasonal Demand Trends
- Peak booking periods were identified
- ADR increased during high-demand seasons
- Weekend pricing improved profitability

### 🔹 Market Segment Analysis
- Online Travel Agencies generated the highest bookings
- Corporate customers showed better retention
- Group bookings had lower cancellation rates

---

#  Machine Learning Analysis

Machine learning models were developed to predict booking cancellations and support pricing optimization.

##  Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

##  Features Used
- Lead Time
- ADR
- Deposit Type
- Customer Type
- Market Segment

---

#  Power BI Dashboards

# 1️ Customer Retention Dashboard

## Dashboard Features
- Cancellation trends
- Customer segmentation
- Retention analysis
- Lead time vs cancellation
- Repeat vs new guest analysis

<img width="1432" height="792" alt="Customer Retention Dashboard" src="https://github.com/user-attachments/assets/9cc27dc2-0b74-480d-be27-d60b35bea637" />


---

# 2️ Dynamic Pricing Dashboard

## Dashboard Features
- Revenue trends
- ADR trends
- Seasonality analysis
- Market segment pricing
- Revenue impact analysis

<img width="1432" height="795" alt="Dynamic Pricing Dashboard" src="https://github.com/user-attachments/assets/c56ccd2c-99af-4bbe-94ff-ad47cc812796" />


---

#  Business Recommendations

##  Customer Retention Strategy
- Implement loyalty programs
- Use personalized customer campaigns
- Reduce cancellation risk through deposit strategies

##  Dynamic Pricing Strategy
- Apply seasonal pricing adjustments
- Increase ADR during high-demand periods
- Use predictive demand forecasting

---

#  Future Enhancements

- Real-time pricing engine
- Advanced forecasting models
- Deep learning churn prediction
- Live booking system integration

---

#  Project Structure

```bash
project/
│
├── data/
│   ├── Uncleaned hotel_bookings.csv
│   └── cleaned_hotel_bookings.csv
│
├── notebooks/
│   ├── EDA_hotel_bookings.ipynb
│   ├── Customer Retention and Dynamic Pricing Analysis.ipynb
│   └── ML_customer_retention and dynamic pricing.ipynb
│
├── dashboards/
│   ├── Customer Retention Dashboard.pbix
│   └── Dynamic Pricing Dashboard.pbix
│
└── README.md
```

---

#  Learning Outcomes

Through this project, the following skills were developed:

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Feature engineering
- Machine learning modeling
- Dashboard development
- Business intelligence reporting
- Hospitality analytics



#  Conclusion

This project demonstrates how data analytics and machine learning can transform hotel booking data into strategic business intelligence.

By combining predictive analytics with interactive dashboards, the project supports:

- Customer retention
- Revenue optimization
- Dynamic pricing
- Demand forecasting

This solution creates a strong analytical foundation for modern hospitality revenue management systems.

```
