# Awesome-Banking

A curated list of **publicly available bank-related datasets** for research, analysis, and machine learning projects. All datasets are open-source and freely accessible.

---

## 📖 Table of Contents

1. [Introduction](#introduction)
2. [Dataset Categories](#dataset-categories)
    - [Transaction Data](#transaction-data)
    - [Customer Data](#customer-data)
    - [Fraud Detection](#fraud-detection)
    - [Credit Scoring](#credit-scoring)
    - [Loan Data](#loan-data)
    - [Market Data](#market-data)
    - [Regulatory Data](#regulatory-data)
    - [ATM Data](#atm-data)
    - [Payment Systems](#payment-systems)
    - [Miscellaneous](#miscellaneous)
3. [Notebook](#notebook)
4. [Contributing](#contributing)
5. [License](#license)

---

## Introduction

📌 Welcome to **Awesome-Banking**! This repository provides an extensive collection of bank-related datasets to facilitate research in financial services, including customer behavior, fraud detection, credit scoring, and more.

Whether you're working on machine learning models, performing data analysis, or seeking real-world financial datasets, this repository is a one-stop resource.

💡 **Why this list?**
- Access over **100+ diverse datasets**
- Explore datasets across multiple domains in banking
- Accelerate your research and machine learning projects

---

## Dataset Categories
📂 This section classifies datasets into distinct categories based on their characteristics and application domains. Each category is tailored to specific research needs, enabling comprehensive analysis and benchmarking across various machine-learning tasks. These categories encompass diverse data types, including structured and unstructured information, facilitating model development for tasks like classification, prediction, and pattern recognition.

### Transaction Data 
💰 This category includes datasets related to financial transactions across various domains such as banking, e-commerce, and payment systems. These datasets are commonly used for tasks like fraud detection, customer behavior analysis, and transaction pattern recognition. They typically contain attributes like transaction amount, timestamps, merchant details, customer IDs, and geographical information. Researchers and practitioners use these datasets to develop and benchmark algorithms for anomaly detection, risk assessment, and financial forecasting.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| Bank Account Transaction Data | A synthetic dataset of bank account transactions. | [Kaggle](https://www.kaggle.com/datasets/ealaxi/banksim1) | CSV |
| Credit Card Transactions for Fraud Detection | A dataset of credit card transactions with labeled fraud cases. | [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) | CSV |
| PaySim: Financial Fraud Simulation Data | A synthetic dataset simulating mobile money transactions. | [Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1) | CSV |
| Bank Marketing Dataset | Data related to direct marketing campaigns of a Portuguese bank. | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) | CSV |
| Online Payments Fraud Detection Dataset | A dataset of online payment transactions with fraud labels. | [Kaggle](https://www.kaggle.com/datasets/jainilcoder/online-payments-fraud-detection-dataset) | CSV |
| Synthetic Financial Transactions | A synthetic dataset of financial transactions. | [Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1) | CSV |
| European Bank Transactions | A dataset of transactions from a European bank. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/european-bank-transactions) | CSV |
| Retail Banking Transactions | A dataset of retail banking transactions. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/retail-banking-transactions) | CSV |
| Mobile Money Transactions | A dataset of mobile money transactions. | [Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1) | CSV |
| E-commerce Transactions | A dataset of e-commerce transactions. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/ecommerce-transactions) | CSV |

---

### Customer Data
🧑Customer data includes information related to individual or corporate clients, encompassing demographic details, transaction history, behavioral patterns, and customer profiles. This data is crucial for customer segmentation, personalized marketing, churn prediction, and improving customer service.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| Bank Customer Churn Dataset | Data on bank customers and their churn status. | [Kaggle](https://www.kaggle.com/datasets/santoshd3/bank-customers) | CSV |
| Bank Customer Segmentation Data | Dataset for clustering bank customers based on demographics and behavior. | [Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata) | CSV |
| Customer Personality Analysis Dataset | Data for analyzing customer behavior and preferences. | [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) | CSV |
| Bank Customer Feedback Dataset | Customer feedback data for sentiment analysis. | [Kaggle](https://www.kaggle.com/datasets/ramkumarr02/bank-customer-feedback) | CSV |
| Bank Customer Demographic Data | Demographic data of bank customers. | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) | CSV |
| Customer Lifetime Value Dataset | Data for calculating customer lifetime value. | [Kaggle](https://www.kaggle.com/datasets/zeesolver/customer-lifetime-value) | CSV |
| Customer Interaction Data | Data on customer interactions with the bank. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/customer-interaction-data) | CSV |
| Customer Risk Profiles | Data on customer risk assessments. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/customer-risk-profiles) | CSV |
| Customer Product Usage | Data on products used by customers. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/customer-product-usage) | CSV |
| Customer Onboarding Data | Data on customer onboarding processes. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/customer-onboarding-data) | CSV |

---

### Fraud Detection
🔍 Fraud detection datasets contain records of legitimate and fraudulent activities across various financial services. This data supports the development and evaluation of models designed to identify and mitigate fraudulent transactions, unusual patterns, and security breaches in real time.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| IEEE-CIS Fraud Detection Dataset | A large dataset for fraud detection in financial transactions. | [Kaggle](https://www.kaggle.com/c/ieee-fraud-detection/data) | CSV |
| Synthetic Financial Dataset for Fraud Detection | A synthetic dataset designed for fraud detection. | [Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1) | CSV |
| Credit Card Fraud Detection Dataset | A dataset of credit card transactions with fraud labels. | [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) | CSV |
| Financial Fraud Detection Dataset | A dataset for detecting fraudulent financial activities. | [Kaggle](https://www.kaggle.com/datasets/ntnu-testimon/paysim1) | CSV |
| Money Laundering Detection Dataset | A dataset for detecting money laundering activities. | [Kaggle](https://www.kaggle.com/datasets/ntnu-testimon/paysim1) | CSV |
| Identity Theft Dataset | Data related to identity theft in banking. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/identity-theft-dataset) | CSV |
| Phishing Attack Data | Data on phishing attacks targeting bank customers. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/phishing-attack-data) | CSV |
| Fraudulent Transactions Dataset | Dataset of flagged fraudulent transactions. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/fraudulent-transactions) | CSV |
| Anomaly Detection Data | Data for detecting anomalies in transactions. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/anomaly-detection-data) | CSV |
| Fraud Case Studies | Case studies on bank fraud incidents. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/fraud-case-studies) | CSV |

---

### Credit Scoring
💳 Credit scoring data includes customer financial histories, credit applications, and repayment behavior. This category is used to develop models for assessing creditworthiness, predicting loan defaults, and automating risk assessment processes.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| Give Me Some Credit Dataset | A dataset for predicting credit risk. | [Kaggle](https://www.kaggle.com/c/GiveMeSomeCredit/data) | CSV |
| Home Credit Default Risk Dataset | A dataset for predicting the likelihood of loan default. | [Kaggle](https://www.kaggle.com/c/home-credit-default-risk/data) | CSV |
| German Credit Dataset | A dataset for credit risk analysis. | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data)) | CSV |
| Lending Club Loan Data | A dataset of loans issued by Lending Club. | [Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club) | CSV |
| Credit Card Approval Dataset | A dataset for predicting credit card approval. | [Kaggle](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction) | CSV |
| Credit Risk Analytics Dataset | A dataset for credit risk analytics. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/credit-risk-analytics) | CSV |
| Credit Utilization Dataset | Data on credit utilization rates. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/credit-utilization) | CSV |
| Credit Report Dataset | Sample credit report data. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/credit-report-data) | CSV |
| Credit Default Dataset | Data on credit defaults. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/credit-default-data) | CSV |
| Credit Limit Dataset | Data on credit limits assigned to customers. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/credit-limit-data) | CSV |

---

### Loan Data
📈 Loan datasets capture information on loan applications, approvals, repayment statuses, and borrower profiles. This data is essential for analyzing lending patterns, predicting defaults, and optimizing credit risk models.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| Lending Club Loan Dataset | A dataset of loans issued by Lending Club. | [Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club) | CSV |
| Peer-to-Peer Lending Dataset | A dataset of P2P lending transactions. | [Kaggle](https://www.kaggle.com/datasets/zhijinzhai/peer-to-peer-lending-dataset) | CSV |
| Small Business Loan Data | A dataset of loans issued to small businesses. | [Kaggle](https://www.kaggle.com/datasets/mirbektoktogaraev/small-business-loans) | CSV |
| Student Loan Dataset | A dataset of student loans. | [Kaggle](https://www.kaggle.com/datasets/wsj/student-loans) | CSV |
| Mortgage Loan Dataset | A dataset of mortgage loans. | [Kaggle](https://www.kaggle.com/datasets/zhijinzhai/mortgage-loan-dataset) | CSV |
| Auto Loan Dataset | A dataset of auto loans. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/auto-loan-data) | CSV |
| Personal Loan Dataset | A dataset of personal loans. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/personal-loan-data) | CSV |
| Loan Repayment Dataset | Data on loan repayment schedules. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/loan-repayment-data) | CSV |
| Loan Performance Dataset | Data on the performance of loans over time. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/loan-performance-data) | CSV |
| Loan Approval Dataset | Data on loan approval processes. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/loan-approval-data) | CSV |

---

### Market Data
📊 Market data consists of financial market information, including stock prices, interest rates, foreign exchange rates, and economic indicators. It is widely used for market trend analysis, investment decision-making, and the development of predictive financial models.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| Yahoo Finance Stock Data | Historical stock market data. | [Yahoo Finance](https://finance.yahoo.com/) | CSV |
| Federal Reserve Economic Data (FRED) | Economic data from the Federal Reserve. | [FRED](https://fred.stlouisfed.org/) | CSV |
| World Bank Open Data | Global financial and economic data. | [World Bank](https://data.worldbank.org/) | CSV |
| Cryptocurrency Market Data | Historical data for various cryptocurrencies. | [Kaggle](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory) | CSV |
| Global Financial Data | A comprehensive dataset of global financial markets. | [Kaggle](https://www.kaggle.com/datasets/borismarjanovic/global-financial-data) | CSV |
| Stock Market Data | Data on stock market performance. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/stock-market-data) | CSV |
| Bond Market Data | Data on bond markets. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/bond-market-data) | CSV |
| Forex Data | Foreign exchange market data. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/forex-data) | CSV |
| Commodity Market Data | Data on commodity markets. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/commodity-market-data) | CSV |
| Interest Rate Data | Data on interest rates over time. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/interest-rate-data) | CSV |

---

### Regulatory Data
📋 Regulatory datasets include compliance-related information mandated by financial authorities. This data aids in ensuring adherence to legal frameworks, improving transparency, and developing models for regulatory reporting and compliance monitoring.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| Basel III Compliance Data | Data related to Basel III regulatory requirements. | [World Bank](https://data.worldbank.org/) | CSV |
| Anti-Money Laundering (AML) Data | Data on AML regulations and compliance. | [Kaggle](https://www.kaggle.com/datasets/ntnu-testimon/paysim1) | CSV |
| Financial Regulatory Reports | Reports on financial regulations. | [Federal Reserve](https://www.federalreserve.gov/) | PDF/CSV |
| Know Your Customer (KYC) Data | Data related to KYC processes. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/kyc-data) | CSV |
| Tax Compliance Data | Data on tax compliance in banking. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/tax-compliance-data) | CSV |
| Financial Reporting Data | Data on financial reporting requirements. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/financial-reporting-data) | CSV |
| Audit Data | Data from bank audits. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/audit-data) | CSV |
| Regulatory Fines Data | Data on fines imposed on banks. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/regulatory-fines-data) | CSV |
| Capital Adequacy Data | Data on capital adequacy ratios. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/capital-adequacy-data) | CSV |
| Stress Testing Data | Data used for stress testing in banks. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/stress-testing-data) | CSV |

---

### ATM Data
🏧 ATM datasets provide insights into cash withdrawal patterns, transaction volumes, and machine performance. This data is valuable for optimizing ATM placements, predicting cash demands, and monitoring system performance.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| ATM Transaction Data | A dataset of ATM transactions. | [Kaggle](https://www.kaggle.com/datasets/zhijinzhai/atm-transaction-data) | CSV |
| ATM Location Data | Data on ATM locations. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-location-data) | CSV |
| ATM Cash Withdrawal Data | Data on cash withdrawals from ATMs. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-cash-withdrawal-data) | CSV |
| ATM Maintenance Data | Data on ATM maintenance schedules. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-maintenance-data) | CSV |
| ATM Fraud Data | Data on fraud incidents at ATMs. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-fraud-data) | CSV |
| ATM Usage Patterns | Data on usage patterns of ATMs. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-usage-patterns) | CSV |
| ATM Network Data | Data on ATM networks. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-network-data) | CSV |
| ATM Downtime Data | Data on ATM downtime incidents. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-downtime-data) | CSV |
| ATM Security Data | Data on ATM security measures. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-security-data) | CSV |
| ATM Customer Behavior | Data on customer behavior at ATMs. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/atm-customer-behavior) | CSV |

---

### Payment Systems
🧾 Payment systems data encompasses transaction records from digital payments, wire transfers, and point-of-sale systems. It is used to analyze transaction flows, detect anomalies, and improve payment processing efficiency.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| SWIFT Transaction Data | A dataset of SWIFT transactions. | [Kaggle](https://www.kaggle.com/datasets/zhijinzhai/swift-transaction-data) | CSV |
| ACH Transaction Data | Data on ACH transactions. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/ach-transaction-data) | CSV |
| Real-Time Payment Data | Data on real-time payment systems. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/real-time-payment-data) | CSV |
| Payment Gateway Data | Data from payment gateways. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/payment-gateway-data) | CSV |
| Cryptocurrency Payment Data | Data on cryptocurrency payments. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/cryptocurrency-payment-data) | CSV |
| Mobile Wallet Data | Data on mobile wallet transactions. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/mobile-wallet-data) | CSV |
| Contactless Payment Data | Data on contactless payments. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/contactless-payment-data) | CSV |
| Payment Fraud Data | Data on payment fraud incidents. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/payment-fraud-data) | CSV |
| Payment Reconciliation Data | Data on payment reconciliation processes. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/payment-reconciliation-data) | CSV |
| Payment System Performance | Data on the performance of payment systems. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/payment-system-performance) | CSV |

---

### Miscellaneous
📦 This category includes datasets that do not fit neatly into the other classifications but are still relevant for financial research. Examples include customer service logs, operational data, and specialized datasets for niche applications.

| Dataset Name | Description | Source | Format |
|--------------|-------------|--------|--------|
| Bank Marketing Dataset | Data related to direct marketing campaigns of a Portuguese bank. | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) | CSV |
| Banking Industry Reports | Reports on the banking industry. | [World Bank](https://data.worldbank.org/) | PDF/CSV |
| Bank Branch Data | Data on bank branch locations and performance. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/bank-branch-data) | CSV |
| Employee Data | Data on bank employees. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/employee-data) | CSV |
| Customer Support Data | Data on customer support interactions. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/customer-support-data) | CSV |
| Bank Marketing Campaign Data | Data on bank marketing campaigns. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/bank-marketing-campaign-data) | CSV |
| Social Media Data | Data from bank social media channels. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/social-media-data) | CSV |
| Customer Loyalty Data | Data on customer loyalty programs. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/customer-loyalty-data) | CSV |
| Banking App Usage Data | Data on the usage of banking apps. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/banking-app-usage-data) | CSV |
| Customer Onboarding Data | Data on customer onboarding processes. | [Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/customer-onboarding-data) | CSV |

---

## Notebook 
### 📓(Coming Soon)
This section will provide a collection of interactive Jupyter notebooks designed to help you explore, analyze, and visualize various financial datasets. Each notebook will include step-by-step guides for tasks such as data preprocessing, feature engineering, model training, and evaluation.

You will find notebooks covering a range of use cases. Stay tuned—these notebooks will be available soon to accelerate your financial data science workflows!

## Installation
🛠️ Follow these steps to set up the environment and access the datasets and notebooks:

### Step 1: Clone the Repository
```bash
git clone <your-repository-url>
cd <your-repository-name>
```

### Step 2: Set Up a Virtual Environment (Optional but Recommended)
Create and activate a virtual environment to isolate dependencies:

Linux/macOS:
```bash
python -m venv venv
source venv/bin/activate
```
Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
pip install jupyter
```


## Contributing

🤝 Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## License

📜 This project is licensed under the [MIT License](LICENSE).

---

🚀 **Happy Analyzing!**

