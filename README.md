# Hotel Booking Demand Analysis: EDA and Statistical Hypothesis Testing

## Project Overview
This project performs Exploratory Data Analysis (EDA), data cleaning, data visualization, and statistical hypothesis testing on the Hotel Booking Demand dataset.

The objective is to identify hotel booking patterns, cancellation trends, customer behavior, and pricing insights using Python.

## Dataset
- Dataset: Hotel Booking Demand
- Source: [Kaggle – Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- Original records: 119,390
- Original features: 32

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- SciPy
- Jupyter Notebook

## Project Structure
```text
Hotel_Booking_EDA_Statistical_Analysis/
├── dataset/
├── notebooks/
├── outputs/
├── README.md
└── requirements.txt
```

## Project Workflow
1. Dataset loading and inspection
2. Missing-value analysis and treatment
3. Duplicate and invalid-record handling
4. Exploratory Data Analysis
5. Data visualization
6. Statistical hypothesis testing
7. Findings and conclusions

## Statistical Tests
- Welch's Independent Samples T-Test
- Chi-Square Test of Independence
- Pearson Correlation Test

## Visualizations
- Hotel booking distribution
- Booking cancellation distribution
- Monthly booking trends
- Correlation heatmap
- ADR comparison by hotel type
- Lead time versus cancellation
- Market segment distribution

## Key Outcomes
The analysis explores booking volumes, cancellation rates, monthly booking patterns, average daily rates, lead times, and customer segments. Actual numerical findings are available in the notebook and exported CSV reports.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```

Open `notebooks/Hotel_Booking_EDA.ipynb` and run the cells in order.

## Author
Shaik Suhail