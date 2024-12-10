Molecular Solubility Prediction Using Machine Learning

This repository contains a complete project for predicting the aqueous solubility of molecules (LogS) based on their molecular descriptors. The project leverages data from the Delaney dataset and applies machine learning to estimate solubility directly from molecular structure.

Features:
Dataset: Includes a pre-processed version of the Delaney solubility dataset with molecular descriptors.
Descriptors: Calculates molecular properties such as LogP, Molecular Weight (MW), Rotatable Bonds (RB), and Aromatic Proportion (AP).

Machine Learning Model: Implements a linear regression model with detailed coefficient analysis and performance metrics.

Custom Web App: Developed a user-friendly Streamlit app for real-time solubility prediction.

Formula: Provides the linear regression formula for calculating LogS:
LogS = Intercept + Coefficient1 * LogP + Coefficient2 * MW + Coefficient3 * RB + Coefficient4 * AP

Visualization: Displays molecular structures and computed descriptors in an interactive interface.

Key Results:
Mean Squared Error (MSE): {Add your value here}
Coefficient of Determination (R²): {Add your value here}

How to Use:
Clone the repository.
Install dependencies from requirements.txt.
Run the Streamlit app to predict LogS for your input molecules.
Acknowledgments:
Dataset Source: Delaney, J. S. ESOL: Estimating Aqueous Solubility Directly from Molecular Structure
Developed by: Onkar Jamma
Contact:
For any queries, reach out via LinkedIn

