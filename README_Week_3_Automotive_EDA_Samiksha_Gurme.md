# Week 3 – Automotive EDA & Data Visualization

**Intern:** Samiksha Gurme  
**Internship:** YuvaIntern – Automotive Data Analysis Specialist  
**Task:** Week 3 – Exploratory Data Analysis (EDA) and Data Visualization

## Project Overview
This project performs exploratory data analysis on automotive performance metrics using Python. The analysis investigates distributions, relationships, trends, correlations, vehicle segmentation and potential anomalies.

## Objectives
- Understand automotive performance variables using descriptive statistics.
- Identify trends and relationships among MPG, horsepower, weight and engine characteristics.
- Compare fuel efficiency across cylinder configurations and vehicle origins.
- Detect unusual observations and potential outliers.
- Create clear and interpretable visualizations.
- Translate EDA results into actionable automotive insights.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / VS Code

## Dataset
The included `automotive_eda_sample.csv` is a **representative demonstration dataset** created for this report. It contains 240 vehicle-level records with:
- `mpg`
- `cylinders`
- `displacement`
- `horsepower`
- `weight`
- `acceleration`
- `model_year`
- `origin`

For a final public-data submission, the dataset can be replaced with a verified public automotive dataset such as the UCI Auto MPG dataset.

## Analysis Performed
1. Data loading and inspection
2. Data-type and quality checks
3. Missing-value and duplicate checks
4. Descriptive statistics
5. Distribution analysis
6. Group comparisons
7. Scatter-plot relationship analysis
8. Model-year trend analysis
9. Correlation heatmap
10. Outlier/anomaly review
11. Findings and actionable insights

## Visualizations
The report includes:
1. Fuel-efficiency distribution
2. Horsepower box plot
3. Cylinder configuration counts
4. Average MPG by cylinders
5. Horsepower vs MPG
6. Weight vs MPG
7. Average MPG by model year
8. Average MPG by origin
9. Correlation heatmap
10. Displacement vs horsepower

## How to Run

### 1. Install Python packages
```bash
pip install pandas numpy matplotlib
```

### 2. Clone the repository
```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
cd <YOUR-REPOSITORY-NAME>
```

### 3. Run the Python script
```bash
python week3_automotive_eda.py
```

## Repository Structure
```text
Week-3-Automotive-EDA/
│
├── Week_3_Automotive_EDA_11_Page_Professional_Samiksha_Gurme.pdf
├── automotive_eda_sample.csv
├── week3_automotive_eda.py
└── README.md
```

## Key Insights
- Vehicle weight and horsepower show an inverse relationship with fuel efficiency in the representative dataset.
- Cylinder configuration provides useful vehicle segmentation.
- Engine displacement and horsepower are positively related.
- Model-year comparisons can reveal changes in average efficiency.
- EDA helps identify variables suitable for later predictive modeling.

## Important Note
The report's figures are based on a representative dataset for demonstration. They should not be presented as results from a public source unless the dataset is replaced and the analysis is rerun on the verified public data.

## Author
**Samiksha Gurme**
