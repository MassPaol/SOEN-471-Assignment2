# SOEN-471-Assignment2

## About
This repository contains Assignment 2 for SOEN 471 at Concordia University.

The project focuses on e-commerce analytics using:
- Data pre-processing on user-product interaction data.
- User-based collaborative filtering with cosine similarity.
- Association rule mining using Apriori/FP-Growth.
- Visualizations for similarity, itemsets, and recommendations.

## Team
Team Number: 56

- Ryan Cheung - 40282200
- Massimo Paolini - 40280323
- Ammar Ranko - 40281232
- Reuven Minciotti - 40252872
- Elif Sag Sesen - 40283343

## Set Up Project
### 1. Clone the repository
```bash
git clone https://github.com/MassPaol/SOEN-471-Assignment2.git
cd SOEN-471-Assignment2
```

### 2. Create and activate a virtual environment (recommended)
Windows (PowerShell):
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend jupyter ipykernel
```

## Run Project
This assignment is implemented in a Jupyter notebook.

### Option A: Run in VS Code
1. Open the repository in VS Code.
2. Open assignment2_notebook.ipynb.
3. Select your Python kernel/virtual environment.
4. Run all cells from top to bottom.

### Option B: Run in Jupyter
```bash
jupyter notebook
```
Then open assignment2_notebook.ipynb and run all cells in order.

## Dependencies
Main Python libraries used in this project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- mlxtend
- jupyter
- ipykernel

## File Structure
```text
SOEN-471-Assignment2/
|-- assignment2_notebook.ipynb
|-- README.md
|-- data/
|   |-- ecommerce_user_data.csv
|   |-- product_details.csv
```

## Outputs
When the notebook is executed, it produces:
- Data cleaning summaries and dataset shape/type checks.
- User-item matrix and aggregated user-category statistics.
- User similarity matrix and heatmap.
- Top-N product recommendations for a target user (example: U000).
- Evaluation metrics for recommender quality (Precision@K and Coverage).
- Frequent itemsets and association rules with support/confidence/lift.
- Visualizations including:
	- User similarity heatmap
	- Top frequent itemsets charts
	- Top recommendation bar chart
