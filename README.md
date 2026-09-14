# Sales and Demand Forecasting ML Model

## Project Overview

This project builds an end-to-end sales forecasting pipeline using the Superstore Sales Dataset from Kaggle.

The goal is to forecast future monthly sales using both Machine Learning and Time Series forecasting models while following proper forecasting practices such as chronological train-test splitting and prevention of data leakage.

---

## Dataset

Dataset:

Superstore Sales Dataset

Source:

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset is **not included** in this repository.

After downloading it from Kaggle, place it here:

```
data/raw/Sample - Superstore.csv
```

---

## Project Objectives

This project performs:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis
- Monthly Sales Aggregation
- Feature Engineering
- Forecasting
- Model Evaluation
- Future Sales Prediction
- Business Insights

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Jupyter Notebook
- Git
- GitHub

---

## Project Structure

```text
superstore-sales-forecasting/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── 01_superstore_forecasting.ipynb
│
├── outputs/
│   ├── figures/
│   └── tables/
│
├── models/
│
├── src/
│
├── .gitignore
├── README.md
└── requirements.txt
```

---

## Methodology

- Data Cleaning
- Exploratory Data Analysis
- Monthly Aggregation
- Feature Engineering
- Forecasting Models

---

### Model Evaluation

Models were evaluated using:

- MAE
- RMSE
- MAPE

The best model (Exponential Smoothing) was selected using the lowest RMSE.

---

## Future Forecast

| Forecast | Value |
|----------|------:|
| Forecast Period | 2018-01 - 2018-12 |
| Total Forecast Sales | 910,080.63 |
| Average Monthly Sales | 75,840.05 |
| Highest Forecast Month | December |

---

## Business Insights

The forecast can help management with:

### Inventory

Increase inventory before expected high-demand periods.

### Staffing

Schedule more employees during forecasted busy months.

### Budgeting

Estimate future revenue and cash flow.

### Promotions

Plan marketing campaigns during slower months.

---

## Limitations

- Forecast uses historical sales only.
- External variables were not included.
- Forecast is at total monthly sales level.

---

## Future Improvements

Possible future work includes:

- Product-level forecasting
- Category forecasting
- Regional forecasting
- Dashboard deployment

---

## How to Run This Project

Clone the repository:

```bash
git clone https://github.com/sisayyigezu/sales-forecasting-model.git
```

Move into the project:

```bash
cd sales-forecasting-model
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it.

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Download the dataset from Kaggle and place it here:

```
data/raw/Sample - Superstore.csv
```

Open:

```
notebooks/01_superstore_forecasting.ipynb
```

Run every notebook cell from top to bottom.

---

## Author

Sisay Yigezu

GitHub:

https://github.com/sisayyigezu
