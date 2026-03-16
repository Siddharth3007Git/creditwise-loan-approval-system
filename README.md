💳 CreditWise Loan Approval System
> An intelligent ML-powered loan approval prediction system built for **SecureTrust Bank** to automate and improve loan decision-making.
---
🧠 Problem Statement
SecureTrust Bank manually reviews hundreds of loan applications daily — a process that is:
⏱️ Time-consuming
⚖️ Biased & inconsistent
❌ Causes good customers to get rejected
❌ Causes high-risk customers to get approved
This ML system solves the problem by automatically predicting whether a loan should be Approved or Rejected based on applicant data — before final human verification.
---
📊 Dataset Features
Column	Description
`Applicant_ID`	Unique applicant ID
`Applicant_Income`	Monthly income of applicant
`Coapplicant_Income`	Monthly income of co-applicant
`Employment_Status`	Salaried / Self-Employed / Business
`Age`	Applicant age
`Marital_Status`	Married / Single
`Dependents`	Number of dependents
`Credit_Score`	Credit bureau score
`Existing_Loans`	Number of already running loans
`DTI_Ratio`	Debt-to-Income ratio
`Savings`	Savings balance
`Collateral_Value`	Value of collateral provided
`Loan_Amount`	Loan amount requested
`Loan_Term`	Loan duration (months)
`Loan_Purpose`	Home / Education / Personal / Business
`Property_Area`	Urban / Semi-Urban / Rural
`Education_Level`	Graduate / Postgraduate / Undergraduate
`Gender`	Male / Female
`Employer_Category`	Govt / Private / Self
`Loan_Approved` ✅	Target: 1 = Approved, 0 = Rejected
---
🛠️ Tech Stack
Language: Python 🐍
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Environment: Jupyter Notebook
---
📁 Project Structure
```
creditwise-loan-approval-system/
├── credit_wise.ipynb          # Main ML notebook
├── loan_approval_data.csv     # Dataset
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies
└── .gitignore                 # Files to ignore
```
---
▶️ How to Run
1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/creditwise-loan-approval-system.git
cd creditwise-loan-approval-system
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Launch the notebook
```bash
jupyter notebook credit_wise.ipynb
```
---
🔍 ML Workflow
Data Loading & Exploration — Understanding the dataset
Data Preprocessing — Handling missing values, encoding, scaling
Exploratory Data Analysis (EDA) — Visualizations & insights
Model Building — Training classification models
Model Evaluation — Accuracy, Precision, Recall, F1-Score
Prediction — Predicting loan approval for new applicants
---
📈 Models Used
Logistic Regression
Decision Tree
Random Forest
(+ any others used in the notebook)
---
👨‍💻 Author
Role: Machine Learning Engineer
Project: CreditWise Loan System — SecureTrust Bank
---
