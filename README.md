# MedTourEasy_Internship
The project done during the internship
🖐 Do Left-Handed People Really Die Younger? – A Bayes’ Theorem Investigation
📌 Project Overview
This project investigates the long-standing claim that left-handed people die, on average, nine years younger than right-handed people — a result famously reported in a 1991 study.
Using Bayes’ Theorem and demographic probability distributions, we revisit the claim to determine whether it’s supported by data or if historical/social biases skewed the results.

Our analysis found the actual difference to be only 2.3 years, not 9 — and most of that is due to generational changes in handedness reporting, not inherent biological factors.
📂 Repository Contents
left_handed_analysis.ipynb – Jupyter Notebook containing all calculations, probability derivations, and visualizations.

project_report.docx – Word document summarizing the project, methods, results, and conclusions in a formal report format.

🛠 Methodology
Collected demographic data on age-at-death distributions and handedness prevalence.

Applied Bayes’ Theorem to compute:

Probability of being a certain age given handedness.

Probability of handedness given age.

Weighted probability distributions to calculate average age at death for both left- and right-handed individuals.

Compared results with the original 1991 claim.

📊 Key Findings
Original claim: Left-handers die 9 years earlier.

Our result: Only 2.3 years difference.

Main cause of the inflated number: generational bias — older people were less likely to self-identify as left-handed.

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/left-handed-analysis.git
cd left-handed-analysis
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook left_handed_analysis.ipynb
Review the complete write-up in project_report.docx.

📚 Dependencies
Python 3.x

Jupyter Notebook

NumPy

Pandas

Matplotlib / Seaborn

Install dependencies with:

bash
Copy
Edit
pip install -r requirements.txt
