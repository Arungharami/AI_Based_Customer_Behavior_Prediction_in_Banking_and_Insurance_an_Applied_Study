# AI-Based Customer Behavior Prediction in Banking and Insurance

Applied machine learning study for predicting customer churn, policy lapse, cross-sell acceptance, and default/claim risk with explainability and fairness review.

![AI Predictive Analytics](https://img.shields.io/badge/AI-Predictive%20Analytics-blue)
![Financial Services](https://img.shields.io/badge/Domain-Banking%20%26%20Insurance-0f766e)
![Explainable AI](https://img.shields.io/badge/XAI-SHAP-purple)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)

## Live Demo / Related Links

No live demo is currently published for this repository.

- Repository: https://github.com/Arungharami/AI_Based_Customer_Behavior_Prediction_in_Banking_and_Insurance_an_Applied_Study
- Lead.AI: https://www.lead-ai.us
- GitHub: https://github.com/Arungharami
- Hugging Face: https://huggingface.co/arun-gharami
- Lead.AI Labs: https://huggingface.co/lead-ai-labs
- Google Scholar: https://scholar.google.com/citations?user=uy4i5soAAAAJ&hl=en

## Overview

This repository contains an applied research notebook for customer behavior prediction in banking and insurance. The notebook builds a synthetic financial-services dataset, engineers customer-level features, trains classification models, evaluates predictive performance, and explores explainability and fairness analysis.

The project is best understood as a research and portfolio artifact rather than a production application. It demonstrates how predictive analytics can support customer retention, product targeting, claims review, and risk-monitoring workflows when paired with responsible AI practices.

## Problem Solved

Banks and insurers need to identify customer and risk events early enough to act. Common use cases include churn prevention, policy lapse detection, cross-sell targeting, default risk review, and claim-risk prioritization.

The challenge is not only building a model. A useful financial-services workflow also needs clean feature windows, leakage-aware labels, class-imbalance handling, interpretable outputs, and fairness checks across customer groups. This project shows a notebook-based approach to that full workflow.

## Key Features

| Feature | Description |
| --- | --- |
| Synthetic customer dataset | Generates banking and insurance behavior records for experimentation without exposing real customer data |
| Multi-outcome prediction | Covers churn, policy lapse, cross-sell acceptance, and combined default/claim risk |
| Feature and outcome windows | Uses an 18-month feature window and 6-month outcome window to reduce leakage risk |
| Feature engineering | Builds aggregate, trend, recency, interaction, banking, insurance, and demographic signals |
| Multiple model families | Experiments with Logistic Regression, Random Forest, and XGBoost classifiers |
| Explainability | Includes SHAP-oriented model interpretation workflow notes |
| Fairness review | Includes fairness analysis concepts across age band, region, and customer segment |
| Portfolio documentation | Frames the notebook for recruiters, clients, academic reviewers, and applied AI portfolio review |

## Tech Stack

| Area | Tools |
| --- | --- |
| Language | Python |
| Environment | Jupyter Notebook / Google Colab |
| Data workflow | pandas, NumPy |
| Modeling | scikit-learn, XGBoost |
| Explainability | SHAP |
| Fairness analysis | Aequitas-style fairness review |
| Visualization | matplotlib, seaborn |
| Synthetic data | Faker |
| Additional file | Selenium Java sample file |

## Architecture / Folder Structure

```text
AI_Based_Customer_Behavior_Prediction_in_Banking_and_Insurance_an_Applied_Study/
|-- AI_Based_Customer_Behavior_Prediction_in_Banking_and_Insurance_An_Applied_Study_final_.ipynb
|-- README.md
`-- selenium
```

Primary artifact:

- `AI_Based_Customer_Behavior_Prediction_in_Banking_and_Insurance_An_Applied_Study_final_.ipynb` contains the data generation, feature engineering, modeling, evaluation, explainability, and fairness workflow.

Secondary artifact:

- `selenium` appears to be a standalone Java Selenium learning/sample file and is not required for the predictive modeling notebook.

## Setup Instructions

Clone the repository:

```bash
git clone https://github.com/Arungharami/AI_Based_Customer_Behavior_Prediction_in_Banking_and_Insurance_an_Applied_Study.git
cd AI_Based_Customer_Behavior_Prediction_in_Banking_and_Insurance_an_Applied_Study
```

Install the notebook dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn xgboost shap aequitas faker scipy
```

Open the notebook:

```bash
jupyter notebook AI_Based_Customer_Behavior_Prediction_in_Banking_and_Insurance_An_Applied_Study_final_.ipynb
```

Google Colab can also be used by uploading the notebook and running the cells from top to bottom. The repository does not currently include a `requirements.txt`, `environment.yml`, or production application entry point.

## Usage Flow

1. Open the notebook in Jupyter or Google Colab.
2. Install and import the required Python packages.
3. Generate the synthetic banking and insurance customer dataset.
4. Build feature and outcome windows from the monthly customer records.
5. Engineer aggregate, trend, recency, and interaction features.
6. Train Logistic Regression, Random Forest, and XGBoost models.
7. Evaluate classification metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
8. Review SHAP/explainability and fairness-analysis sections.
9. Use findings as research notes, portfolio evidence, or a starting point for a more reproducible modeling package.

## Screenshots

Screenshots are not currently included in the repository.

Recommended future screenshots:

- Notebook table of contents or workflow summary
- Synthetic dataset preview
- Model comparison table
- Confusion matrix examples
- SHAP summary plot
- Fairness metric comparison plot

## Results / Metrics / Model Notes

The notebook contains experimental model-training and evaluation cells, but this README does not present final benchmark claims because the repository does not include a cleaned, reproducible results export.

Observed notebook characteristics:

- Synthetic dataset size: 10,000 customers across 24 months, producing 240,000 monthly records.
- Feature window: first 18 months.
- Outcome window: final 6 months.
- Target variables: `Churn`, `PolicyLapse`, `CrossSellAccept`, and combined `Default/ClaimRisk`.
- Model families: Logistic Regression, Random Forest, and XGBoost.
- Evaluation metrics: accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and fairness-oriented group comparisons.

Before using this project as a formal research result, add a reproducible execution path, export the final metrics table, and document any failed or exploratory notebook cells separately from the final pipeline.

## Security Notes

- No production secrets are required to run the notebook.
- The dataset is synthetic and should not be treated as real customer data.
- Do not commit real banking, insurance, customer, claims, or transaction records to this repository.
- The standalone Selenium sample references public demo-site login values. Replace any real credentials with environment variables before adapting it for private systems.
- This project is not approved for regulated financial decision-making without additional privacy, compliance, fairness, security, and model governance review.

## Roadmap

- Add `requirements.txt` or `environment.yml`.
- Clean the notebook into a reproducible final pipeline with a clear table of contents.
- Export verified model metrics and plots into a dedicated `reports/` or `figures/` folder.
- Add a model card describing intended use, limitations, fairness considerations, and monitoring needs.
- Separate or remove the unrelated Selenium sample from the predictive modeling repository.
- Add a lightweight FastAPI or dashboard prototype only after the notebook workflow is stable.

## Author / Contact

**Arun Kumar Gharami**

AI Engineer | Applied Researcher | QA Automation Engineer

- Lead.AI: https://www.lead-ai.us
- GitHub: https://github.com/Arungharami
- Hugging Face: https://huggingface.co/arun-gharami
- Lead.AI Labs: https://huggingface.co/lead-ai-labs
- Google Scholar: https://scholar.google.com/citations?user=uy4i5soAAAAJ&hl=en

## License Note

No license file was confirmed during this documentation pass. Add a license before external reuse, distribution, or collaboration.
