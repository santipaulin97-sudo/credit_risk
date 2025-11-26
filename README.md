📌 Description

The Credit Risk Predictor V26.0 is a complete tool to evaluate loan applications, predict default risk, and generate a detailed, professional PDF report with financial analysis, risk factor justification, and visualizations of amortization and payment capacity.

This system integrates:

Machine learning model based on Random Forest, calibrated with CalibratedClassifierCV.

Automatic data preprocessing pipeline for numerical and categorical features.

Generation of styled PDF reports, ready for analysts or credit committees.

Visualizations including:

Probability of repayment vs default.

Annual loan amortization.

Impact of monthly payments on the applicant’s income.

⚙️ Key Features

Credit risk prediction for individual applicants.

Automated justification with the top 5 most relevant risk factors according to feature importance.

Loan amortization calculation with a breakdown of principal and interest.

Integrated visualizations in the PDF report:

Payment/default probability chart.

Stacked annual amortization chart.

Monthly payment impact on income chart.

🛠️ Usage

Clone the repository:

git clone https://github.com/yourusername/credit-risk-predictor.git
cd credit-risk-predictor


Create a virtual environment and install dependencies:

python -m venv venv
venv\Scripts\activate  # Windows
pip install -r requirements.txt


Run the predictor:

python chatgpt.py


Enter the applicant’s data following the guided prompts.

The tool generates a PDF report: Informe_Riesgo_Crediticio.pdf.

📁 Files

chatgpt.py – Main Python script with ML pipeline, prediction logic, and PDF generation.

models/ – Folder to store trained model and preprocessing metadata.

loan_default.csv – Sample dataset for training/testing.

requirements.txt – Python dependencies for running the project.

📊 Technology Stack

Python 3.10+

pandas, numpy, matplotlib, seaborn

scikit-learn

fpdf2 (PDF generation)
