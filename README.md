# iul-suitability-ml-fintech
# Financial Fitness AI – Predicting IUL Suitability with Machine Learning

**Author:** Roman Dobczansky  
[GitHub Profile](https://github.com/roboy88) | [LinkedIn](https://linkedin.com/in/roman-w-dobczansky) | [Substack Article](https://your-substack-url-if-published)

---

## Overview

This project explores how **machine learning** can support insurance advisors and fintech applications by predicting a client’s suitability for **Indexed Universal Life (IUL)** insurance.

Combining my experience as a **licensed financial advisor** and **data scientist trained at Rutgers**, this model helps identify potential IUL candidates based on demographic and financial attributes.

---

## Problem Statement

IUL is a powerful but often misunderstood financial tool. It offers:
- Tax-deferred growth
- Principal protection from market losses
- Long-term death benefit and wealth transfer

However, without proper structuring or suitability analysis, it can be misused. This project asks:

> _Can we use machine learning to determine whether a client is a good fit for an IUL policy based on key profile features?_

---

## Features Used

The model uses 4 inputs:

- `age` (numeric)
- `income` (numeric)
- `credit_score` (numeric)
- `market_risk_tolerance` (Low, Medium, High → ordinal encoding)

The binary target variable is:  
- `iul_recommended` (1 = Yes, 0 = No)

---

## Technology Stack

- **Python**, **Pandas**, **NumPy**
- **scikit-learn** (RandomForestClassifier)
- **Matplotlib**, **Seaborn**
- **Google Colab** (Notebook-ready)
- Projected for future deployment via **Streamlit**

---

## Notebook

Open and run the Colab notebook here:

**[Open in Google Colab](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID)**

Or view the code in this repository:  
`Financial_Fitness_AI_IUL_Classifier.ipynb`

---

## Results

This version uses a synthetic dataset of 500 simulated clients. The baseline model accuracy is ~51% and can be improved with real-world data and class balancing. The notebook includes:

- Confusion matrix
- Precision, recall, and F1-score
- Sample prediction output

---

## Next Steps

Planned enhancements include:
- SHAP model explainability
- Integration of anonymized real client data
- Streamlit app for real-time advisor use
- Optional API deployment

---

## Who This Project Is For

- **Financial advisors** who want to integrate smart modeling into client conversations
- **Fintech startups** building embedded insurance tools
- **Hiring managers** seeking practical, applied ML experience in regulated domains

---

## About the Author

I’m a data scientist and licensed financial professional with experience in insurance strategy, machine learning, and fintech modeling. I’ve sold IUL policies to friends, family, and clients, and own four IULs myself. I believe in merging human-centered advising with data-backed intelligence.

- GitHub: [roboy88](https://github.com/roboy88)
- LinkedIn: [roman-w-dobczansky](https://linkedin.com/in/roman-w-dobczansky)
- Substack: *[Financial Fitness AI – Full Article](https://your-substack-url-if-available)*

---

## License

This project is open for educational and portfolio purposes. Reach out for collaboration or implementation use cases.

---

