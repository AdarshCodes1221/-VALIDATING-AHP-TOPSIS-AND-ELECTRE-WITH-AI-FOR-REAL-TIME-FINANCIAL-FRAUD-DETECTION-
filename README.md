📌 VALIDATING AHP, TOPSIS, AND ELECTRE WITH AI FOR REAL-TIME FINANCIAL FRAUD DETECTION & PREVENTION

Domain: Data Science & Machine Learning
Tech Stack: Python | NumPy | Pandas | Scikit-Learn | AI/ML | MCDM Models

This project integrates AHP, TOPSIS, and ELECTRE multi-criteria decision-making models, enhanced using AI-based fraud detection, to classify financial transactions and rank them based on risk. The framework validates classical decision models using machine learning predictions and evaluates real-time fraud scenarios.

Financial fraud cases are rapidly increasing — In India alone, losses crossed ₹21,367 crore in FY25 and more than 13,000+ banking frauds were recorded, proving the need for intelligent real-time fraud defence. 

Fraud Detection and prevention

🔥 Features

✔ Implementation of AHP, TOPSIS, and ELECTRE MCDM techniques

✔ AI-based fraud detection model (Regression/Classification)

✔ Real-time risk scoring of debit/credit transactions

✔ Outranking & prioritization of fraud cases

✔ Unified workflow combining all three decision models

✔ Future-ready platform for financial institutions



🔧 Installation
Requirements
Python 3.10+
numpy
pandas
scikit-learn


Install dependencies:

pip install -r requirements.txt

🚀 How to Run
python main.py


Output:
✔ Decision ranking (AHP/TOPSIS/ELECTRE)
✔ Fraud prediction result (Legit / Suspicious / High-Risk)

Example usage inside code:

from ahp import ahp_method
from topsis import topsis_method
from electre import electre_method
from ai_model import predict_fraud

🧠 Methodology Overview
1. AHP – Analytical Hierarchy Process

Used for assigning weights to fraud parameters.
Flow:

Pairwise comparison matrix

Eigen values → Eigen vector

Check consistency (CR < 10% → valid)


Fraud Detection and prevention

2. TOPSIS – Real-time Fraud Scoring

Ranks transactions based on closeness to ideal fraud characteristics.
Enhanced by:

Autoencoders for anomaly filtering

Reinforcement learning for threshold tuning


Fraud Detection and prevention

3. ELECTRE – Outranking Based Risk Evaluation

Determines dominance between suspicious transactions.
Steps:

Concordance/discordance index

Outranking relations

Net flow → Final ranking


Fraud Detection and prevention

4. AI Model Validation

ML model used to compare & validate MCDM results.

📊 Key Performance (Sample Study)

Accuracy: 95%

Recall: 88%

Processing time: 50ms/transaction (GPU optimized)


Fraud Detection and prevention

🔄 Unified Workflow
AHP → Assign weights & importance
          ↓
TOPSIS → Detect suspicious transactions (real-time)
          ↓
ELECTRE → Deep investigation via outranking
          ↓
AI Model → Validates & enhances detection accuracy

📌 Future Improvements

Deploy as Web App / REST API

Add XAI explainability dashboards

Integrate Deep Learning models

Live integration with Banking Systems / UPI / CBS

🧾 Authors
Name	PRN
Adarsh Jha	23070122261
