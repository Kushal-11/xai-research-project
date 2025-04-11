# Singapore Education Data Analysis

## Project Overview
This project analyzes Singapore's education data to identify factors influencing reading achievement scores and explore patterns in educational outcomes. The analysis utilizes various exploratory data analysis (EDA) techniques and applies interpretable machine learning models.

## Data Sources
The analysis utilizes the dataset, 'Singapore Data (6721).csv' which contains student performance metrics, demographic information, and various educational factors.

## Repository Structure
- `EDA.ipynb`: Initial exploratory data analysis
- `EDA 2.ipynb`: Advanced exploratory data analysis with ydata-profiling
- `modeling.ipynb`: Machine learning model development and evaluation

## Tools & Libraries
- **Data Processing**: pandas, numpy
- **Data Visualization**: matplotlib, seaborn
- **Exploration**: ydata-profiling (formerly pandas-profiling)
- **Machine Learning**: scikit-learn
- **Interpretability**: SHAP, LIME, PyALE

## Key Features
- Comprehensive data profiling with interactive HTML reports
- Missing value analysis and handling
- Feature correlation analysis
- Distribution visualization
- Principal Component Analysis (PCA)
- Outlier detection and analysis

## Getting Started
```bash
# Clone the repository
git clone https://github.com/Kushal-11/xai-research-project.git

# Navigate to project directory
cd xai-research-project

# Create a virtual environment
python -m venv xai

# Activate the virtual environment
## On Windows
xai\Scripts\activate
## On Linux/Mac
source xai/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebooks
jupyter notebook
```

