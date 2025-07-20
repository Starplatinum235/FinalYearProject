# 🧠 MAOB Inhibitor Prediction for Parkinson’s Disease

This project uses **machine learning** and **cheminformatics** tools to predict the bioactivity (pIC50) of compounds as potential **Monoamine Oxidase B (MAOB)** inhibitors — a promising approach for Parkinson’s disease drug discovery.

## 📌 About the Project

Monoamine Oxidase B is a key target in Parkinson’s disease treatment. This tool provides a way to:
- Upload molecular structures (SMILES)
- Generate molecular descriptors/fingerprints using **PaDEL**
- Predict their pIC50 values using a trained **Random Forest Regression** model

## 🛠️ Tools & Technologies

- Python 🐍
- Streamlit (for the web app)
- PaDEL-Descriptor (for molecular descriptors)
- RDKit (for chemical structure handling)
- Scikit-learn (for ML modeling)
- pandas, numpy, joblib

## 🚀 How to Use

1. Clone the repository
2. Install required Python packages.
3. Make sure **PaDEL-Descriptor.jar** is present in the working directory
4. Run the app.
5. Upload your SMILES `.csv` file and get predictions instantly!

## 📁 Input Format

CSV file with a column named `smiles`. Example:

| smiles               |
|----------------------|
| C1=CC=CC=C1          |
| CC(=O)OC1=CC=CC=C1C(=O)O |

## 📤 Output

- CSV file with predicted **pIC50** values
- Drug-likeness filters applied (Lipinski’s Rule of Five)

## 📄 License

This project is for academic and educational purposes

**Please check my thesis for further clarification.**
