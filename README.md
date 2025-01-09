# **EDA of Credit Card Transactions for Fraud Detection**

## **Problem Statement**
Credit card fraud is a significant concern for financial institutions and consumers alike. Fraudulent activities result in substantial financial losses and diminish customer trust. The goal of this project is to perform Exploratory Data Analysis (EDA) on credit card transaction data to uncover patterns and anomalies that might indicate fraudulent behavior. 

By analyzing the dataset, we aim to gain insights into transaction patterns and identify factors distinguishing fraudulent transactions from legitimate ones.

---

## **Dataset Details**
- **Dataset Name**: Credit Card Fraud Detection Dataset  
- **Source**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description**: The dataset contains transactions made by European cardholders in September 2013. It includes 31 features, such as time, amount, and anonymized numerical features (V1 to V28). The `Class` column indicates whether a transaction is fraudulent (`1`) or legitimate (`0`).

---

## **Key Questions Addressed**
1. How many rows and columns are in the dataset?  
2. What are the column names and their data types?  
3. Are there any missing or null values in the dataset?  
4. How many transactions are fraudulent, and how many are legitimate?  
5. What percentage of transactions are fraudulent?  
6. What are the minimum, maximum, mean, and median values for numerical columns like `Amount`?  
7. What is the maximum transaction amount in the dataset, and is it fraudulent?  
8. Can we create a bar chart showing the count of fraudulent vs. legitimate transactions?  
9. What does the histogram of transaction amounts look like?  
10. Can we use a heatmap to visualize the correlation between numerical features?

---

## **Project Workflow**
### **1. Data Exploration**
- Loaded and inspected the dataset to understand its structure and size.  
- Checked for missing or null values.  

### **2. Statistical Analysis**
- Calculated basic statistics for numerical columns like `Amount`.  
- Investigated the proportion of fraudulent transactions.  

### **3. Visualization**
- Created a bar chart to show the distribution of fraudulent vs. legitimate transactions.  
- Plotted a histogram to analyze the distribution of transaction amounts.  
- Used a heatmap to visualize correlations between numerical features.  

---

## **Findings**
- **Class Imbalance**: The dataset exhibits significant class imbalance, with a very small percentage of fraudulent transactions (~0.17%).  
- **Transaction Amounts**: Fraudulent transactions are not necessarily associated with higher amounts.  
- **Feature Correlations**: Some numerical features (e.g., `V14`, `V17`) show stronger correlations, potentially useful for fraud detection models.  

---

## **Tools and Technologies**
- **Programming Language**: Python  
- **Libraries Used**: pandas, numpy, matplotlib, seaborn  

---

## **Results and Conclusion**
The analysis highlights the importance of understanding transaction patterns and identifying anomalies. These insights can serve as a foundation for building machine learning models to detect fraudulent transactions effectively.

---

## **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone https://github.com/YasirSheikh38/EDA-of-Credit-Card-Transactions-for-FraudDetections.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook file (`EDA_of_Credit_Card_Transactions.ipynb`) to view the analysis.

---

## **Acknowledgments**
- The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- Special thanks to the Machine Learning Group (ULB) for providing the dataset.

---

