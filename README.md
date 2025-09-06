# Credit Score Assessment - Exploratory Data Analysis

## Project Overview
This repository contains a comprehensive **exploratory data analysis (EDA)** of credit score data, identifying patterns, correlations, and insights that can help in understanding factors affecting credit scores.  
The analysis examines relationships between various financial behaviors and credit scores across multiple customer records.

---

## Author
**Kailas Binukumar**  
📧 Email: [kailasbinukumar101@gmail.com](mailto:kailasbinukumar101@gmail.com)

---

## Dataset
- **Size**: 100,000 records spanning across 8 months  
- **Features**: 28 including demographic data, financial behaviors, and credit metrics  
- **Target variable**: `Credit Score` (Categories: *Good, Standard, Poor*)

### Note on Dataset
The original dataset (`dataset-2.csv`) is too large to be included in this repository. To access the dataset:

1. Download from the original source (if available)  
2. Contact the author directly for access  
3. Use a similar credit score dataset from public repositories like [Kaggle](https://www.kaggle.com/)

---

## Data Dictionary
Key fields in the dataset include:

- **ID**: Unique identifier for each entry  
- **Customer_ID**: Unique identifier for each customer  
- **Month**: Month number (1–8)  
- **Age**: Age of the customer (years)  
- **Occupation**: Profession of the customer  
- **Annual_Income**: Annual income (USD)  
- **Monthly_Inhand_Salary**: Monthly in-hand salary (USD)  
- **Num_Bank_Accounts**: Number of bank accounts  
- **Num_Credit_Card**: Number of credit cards  
- **Interest_Rate**: Interest rate on loans/credit  
- **Num_of_Loan**: Number of loans taken  
- **Delay_from_due_date**: Days delayed from payment due date  
- **Num_of_Delayed_Payment**: Number of delayed payments  
- **Credit_Utilization_Ratio**: Credit utilization ratio (%)  
- **Credit_History_Age**: Age of credit history (days)  
- **Payment_Behaviour**: Payment behavior pattern  
- **Credit_Score**: Credit score category (*Poor, Standard, Good*)  

---

## Key Insights

### Credit Score Distribution
- **Standard**: ~53%  
- **Poor**: ~29%  
- **Good**: ~18%  

### Top Factors Affecting Credit Score
- **Credit Utilization Ratio** → Lower utilization correlates with better scores  
- **Payment Behavior** → Consistent payment behavior leads to better scores  
- **Credit History Age** → Longer credit history correlates with better scores  
- **Delay from Due Date** → Fewer days of delay correlates with better scores  

**Summary:** Customers with good credit scores typically maintain **low utilization**, a **longer history**, and **consistent on-time payments**.

---

## Technologies Used
- **Language**: Python 3.x  
- **Libraries**:  
  - Pandas → Data manipulation  
  - NumPy → Numerical operations  
  - Matplotlib & Seaborn → Data visualization  
  - SciPy → Statistical analysis  
  - Scikit-learn → Preprocessing  

---


## Recommendations for Credit Score Improvement
- Maintain **credit utilization below 30%**  
- Practice **consistent payment behavior**  
- **Minimize delays** in payments  
- Build and maintain **credit history**  
- **Diversify credit mix**  
- Limit **credit inquiries**  
- Monitor and reduce **outstanding debt**  
- Always **pay at least the minimum amount**  
- Regularly **monitor credit reports**  
- Manage **income effectively**  

---


---

## Acknowledgements
- Thanks to all contributors and reviewers who provided feedback  
- Special thanks to internship supervisors for their guidance  
