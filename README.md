# Customer Retention Analysis for Subscription Services

## Overview
This project focuses on analyzing customer retention for subscription services using machine learning. The goal is to predict customer churn based on various features such as subscription plans, tenure, and customer behavior.

## Dataset
The dataset contains customer subscription details, including:
- Customer ID (removed during preprocessing)
- Subscription Start Date
- Plan Type (Basic, Standard, Premium)
- Churn Status (Yes/No)

## Technologies Used
- Python (pandas, numpy, sklearn, matplotlib, seaborn)
- Machine Learning (Logistic Regression)
- Tableau (for interactive dashboard visualization)

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/customer-retention-analysis.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the script:
   ```sh
   python analysis.py
   ```

## Project Structure
```
├── data
│   ├── Customer_Subscription.csv
├── src
│   ├── analysis.py
├── notebooks
│   ├── EDA.ipynb
├── visualizations
│   ├── tableau_dashboard.twb
├── README.md
```

## Model Performance
- **Accuracy:** X%
- **Classification Report:** Detailed precision, recall, F1-score.
- **Confusion Matrix:** Visualized in the notebook.

## Tableau Dashboard
An interactive dashboard is created in Tableau to visualize churn patterns. Key insights include:
- Customer distribution by subscription plan
- Monthly churn trends
- Feature importance for churn prediction

## Future Enhancements
- Implement more advanced ML models (Random Forest, XGBoost)
- Improve data preprocessing techniques
- Add more customer behavior features

## Contributors
- Your Name (saiamit8355@gmail.com)

## License
This project is licensed under the MIT License.

