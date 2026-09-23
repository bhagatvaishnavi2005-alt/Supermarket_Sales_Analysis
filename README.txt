# Supermarket Sales Analysis with AI

**Project by : Vaishnavi Bhagat
**Program:** AICTE | IBM SkillsBuild — Data Analytics with AI Academic Internship 2026 (BharatCares)

## Description
This project analyzes supermarket transaction data to uncover business insights around branch performance, product line revenue, customer payment preferences, and sales trends. It then applies a machine learning model (Random Forest Regressor) to predict customer satisfaction (`Rating`) from transaction features, demonstrating how AI can support data-driven retail decisions.

## Dataset
This project uses the structure of the standard **Supermarket Sales** dataset (Invoice ID, Branch, City, Customer type, Gender, Product line, Unit price, Quantity, Tax 5%, Total, Date, Time, Payment, cogs, gross margin percentage, gross income, Rating).

- If you have the official dataset from your Masterclass 4 workbook, place it at `data/supermarket_sales.csv` before running the notebook.
- If no dataset is found at that path, the notebook automatically generates a realistic **synthetic sample dataset** with the same structure so the full pipeline still runs end-to-end.
- Public reference dataset (optional): [Supermarket Sales — Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)

## Technologies Used
- Python 3
- Pandas, NumPy — data handling
- Matplotlib, Seaborn — visualization
- Scikit-learn — machine learning (Random Forest Regressor)
- Jupyter Notebook

## Setup & Run Instructions
1. Clone this repository or download the project files.
2. (Recommended) Create a virtual environment:
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
3. Install dependencies:
   pip install -r requirements.txt
4. Launch Jupyter and open the notebook:
   jupyter notebook YourName_SupermarketSalesAnalysis.ipynb
5. Run all cells from top to bottom (Cell > Run All).

## Key Sections in the Notebook
1. Data loading
2. Data cleaning & preparation
3. Exploratory Data Analysis (branch sales, product line revenue, payment methods, sales trend, ratings, correlations)
4. AI model — Random Forest Regressor predicting customer Rating
5. Business insights & conclusion

## Author
- Name: [Your Full Name]
- Institution: [Your Institution Name]
- Internship: AICTE | IBM SkillsBuild Data Analytics with AI (2026), BharatCares
