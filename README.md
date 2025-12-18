Smartledger AI – Automated Financial Analysis & Fraud Detection Auditor:
Project Overview:

This project is an end-to-end AI-based financial auditing system that automates data validation, anomaly detection, fraud analysis, and compliance checking. It combines financial rule checks, machine learning models, OCR document processing, and visual analytics to simulate a real-world financial audit workflow.

The system is designed to help auditors and analysts identify errors, inconsistencies, unusual patterns, and potential fraud in large financial datasets and documents.

Key Objectives:

Automate financial data cleaning and validation

Detect outliers, mismatched totals, and suspicious transactions

Analyze financial health using ratios and trends

Extract financial data from PDFs, images, and Excel files

Classify financial records using AI models

Generate audit and compliance reports automatically

Features:
1. Data Validation & Cleaning

Duplicate Account ID detection

Missing value analysis

Record type normalization and validation

Date and period standardization

Outlier detection using statistical thresholds

2. Financial Audit Checks:

Parent account vs total reconciliation

Rule-based mismatch detection

AI-generated audit suggestions

Financial ratio calculations (Current Ratio, Debt-Equity Ratio)

Benford’s Law simulation for fraud pattern analysis

3. Visual Analytics:

Time-series transaction analysis

Distribution analysis by record type

Correlation heatmaps

Fraud and error label distribution charts

4. OCR & Document Automation:

Invoice and document text extraction using PaddleOCR

PDF text parsing using PyMuPDF

Excel data ingestion

Automatic file type detection and processing

5. Machine Learning & AI:

Class imbalance handling using Upsampling and SMOTE

Fraud and anomaly classification using:

Random Forest

XGBoost

Model evaluation with classification reports and confusion matrices

Feature importance analysis for model interpretability

6. Audit Reporting & Collaboration:

Automated audit report generation (CSV & Excel)

Timestamped reports for traceability

Reviewer comments and approval tracking

IFRS compliance validation using reference templates

Technologies Used:

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

PaddleOCR

PyMuPDF

OpenPyXL

Imbalanced-learn (SMOTE)
