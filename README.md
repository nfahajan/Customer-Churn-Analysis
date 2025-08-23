# Customer Churn Analysis

## Project Overview

This project analyzes customer churn patterns in a telecommunications company using machine learning and data visualization techniques. The analysis helps identify factors that contribute to customer attrition and provides insights for developing retention strategies.

## Objectives

- Analyze customer churn patterns and identify key factors
- Visualize relationships between customer characteristics and churn behavior
- Provide actionable insights for customer retention strategies
- Demonstrate data cleaning, exploration, and visualization best practices

## Getting Started

### Prerequisites

- Python 3.7+
- Required Python packages (install via pip):

```bash
pip install pandas matplotlib seaborn numpy
```

### Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Ensure your dataset is in the `dataset/` folder

### Running the Analysis

#### Option 1: Python Script

```bash
python customer_churn_analysis.py
```

#### Option 2: Jupyter Notebook

```bash
jupyter notebook Customer_Churn_Analysis.ipynb
```

#### Option 3: Google Colab

- Upload the `.ipynb` file to Google Colab
- Mount your Google Drive if using the dataset from there
- Run all cells

##  Dataset Information

The analysis uses a telecommunications customer dataset with the following key features:

- **Size**: 4,225 customers × 52 features
- **Target Variable**: Churn (Binary: 0 = Stayed, 1 = Churned)
- **Key Features**:
  - Customer demographics (Age, Gender, Senior Citizen status)
  - Service details (Contract type, Internet type, Monthly charges)
  - Usage patterns (Tenure, Monthly GB download, Streaming services)
  - Billing information (Payment method, Paperless billing)

##  Analysis Components

### 1. Data Cleaning & Preprocessing

- Handling missing values
- Converting categorical variables
- Ensuring data type consistency
- Removing duplicates

### 2. Exploratory Data Analysis

- Churn distribution analysis
- Contract type impact on churn
- Tenure analysis
- Monthly charges correlation
- Cross-analysis by various customer segments

### 3. Visualization

- Bar charts for categorical variables
- Histograms for numerical distributions
- Correlation heatmaps
- Comparative analysis plots

## Key Insights

1. Overall Churn Rate: ~26.5% (about 1 in 4 customers leave).
2. Contract Type: Month-to-month contracts have the highest churn.
3. Tenure: Customers within first year are most likely to churn. Long-tenured customers are loyal.
4. Monthly Charges: Higher monthly charges strongly linked to churn.
5. Internet Type: Fiber optic customers churn more than DSL.
6. Payment Method: Electronic check users churn more than auto-pay/credit card users.
7. Paperless Billing: More churn compared to paper billing.
8. Senior Citizens: Slightly higher churn rate.
9. Streaming Services: Streaming TV & movie users churn more.
   Conclusion: Customer drop-off is led by short contracts, high monthly charges, and billing/payment methods. Retention can be improved
   with loyalty programs, discounts for long-term contracts, and better engagement with at-risk segments.

## 🛠 Technical Details

### Libraries Used

- **pandas**: Data manipulation and analysis
- **matplotlib**: Basic plotting and visualization
- **seaborn**: Statistical data visualization
- **numpy**: Numerical computations

### Data Processing Steps

1. Data loading and initial exploration
2. Missing value handling
3. Data type conversion
4. Feature engineering (if applicable)
5. Statistical analysis and visualization

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

