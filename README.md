# Irish Rental Market Analytics (2020-2023)

An end-to-end data analysis project exploring rental price trends across Irish counties using Python, Pandas, and Matplotlib.

## Key Findings
- Rent increased by 47.3% nationally between 2020 and 2023
- Dublin is 69.1% more expensive than the rest of Ireland on average
- Most affordable option: Limerick, 1-bed apartment at EUR1,029/month
- Most expensive county: Dublin at EUR2,288/month average

## Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Git and GitHub

## Project Structure
- data/raw/ — Original dataset
- data/cleaned/ — Cleaned and processed data
- notebooks/analysis.ipynb — Full analysis notebook
- outputs/charts/ — All generated charts
- outputs/key_insights.txt — Summary of findings

## Charts Generated
1. Average Rent by County (2020-2023)
2. Average Rent by Number of Bedrooms
3. Rent Distribution by Property Type
4. Dublin vs Rest of Ireland Comparison

## How to Run
1. Clone the repo
2. Create virtual environment: python -m venv venv
3. Activate: venv\Scripts\activate
4. Install dependencies: pip install -r requirements.txt
5. Open: jupyter notebook notebooks/analysis.ipynb