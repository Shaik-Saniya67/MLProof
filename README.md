🛡️ MLProof — Machine Learning Model Auditor

Evaluate model reliability before trusting its predictions.

MLProof is a Streamlit-based machine learning auditing tool designed to identify potential issues in datasets and machine learning models. It analyzes data quality, class imbalance, data leakage risks, baseline performance, cross-validation, and overfitting indicators to help users understand potential weaknesses before relying on model results.

✨ Key Features

- 🔍 Dataset Discovery — Explore a curated catalog of bundled scikit-learn datasets.
- 📊 Data Profiling — Inspect dataset characteristics and identify potential quality issues.
- ⚖️ Class Imbalance Detection — Highlight uneven class distributions that may affect model evaluation.
- 🚨 Data Leakage Heuristics — Flag potential leakage risks that could lead to misleading performance.
- 🎯 Baseline Evaluation — Establish baseline results for model comparison.
- 🔄 Cross-Validation Analysis — Examine performance across validation folds.
- 📉 Overfitting Indicators — Identify warning signs of a gap between training and validation performance.
- 📋 Audit Findings & Status — Present detected concerns and audit results in a structured interface.
- 📄 Report Generation — Export audit results into supported report formats.

🧰 Tech Stack

- Language: Python
- Frontend: Streamlit
- Data Analysis: Pandas
- Visualization: Plotly
- Machine Learning Utilities: scikit-learn

🏗️ Project Structure

MLProof/
├── core/
│   ├── __init__.py
│   ├── actual_audit.py
│   ├── actual_ui.py
│   ├── audit.py
│   ├── demo.py
│   └── discovery.py
├── reports/
│   ├── __init__.py
│   └── report_generator.py
├── app.py
├── requirements.txt
└── README.md

Architecture Overview

- "app.py" — Main application entry point and Streamlit interface.
- "core/" — Contains auditing logic, dataset discovery, UI components, and demonstration functionality.
- "reports/" — Handles audit report generation and supported export formats.
- "requirements.txt" — Lists the Python dependencies required to run the project.

🚀 Getting Started

Prerequisites

- Python 3.10 or a compatible version supported by the dependencies
- pip package manager

Installation

1. Clone the repository

git clone https://github.com/Shaik-Saniya67/MLProof.git
cd MLProof

2. Install dependencies

pip install -r requirements.txt

3. Launch the application

streamlit run app.py

4. Open the local application

Streamlit will provide a local URL in the terminal, usually:

http://localhost:8501

🎯 Why MLProof?

A machine learning model can produce impressive evaluation scores while still having problems such as data leakage, class imbalance, or inconsistent validation performance.

MLProof aims to make these potential issues easier to inspect through a structured auditing workflow, helping users make more informed decisions about model reliability.

⚠️ Important Note

MLProof is an auditing aid, not a guarantee that a model is correct, unbiased, or production-ready. Automated checks and heuristic findings require interpretation and should be complemented by domain knowledge and appropriate validation.

🔮 Future Enhancements

- Expanded dataset and model support
- More detailed audit visualizations
- Enhanced explanations for detected issues
- Additional evaluation metrics and validation strategies
- Improved report customization

👩‍💻 Author

Saniya Shaik

GitHub: "@Shaik-Saniya67" (https://github.com/Shaik-Saniya67)

---

MLProof — Because a good score is not the same as a trustworthy model.
