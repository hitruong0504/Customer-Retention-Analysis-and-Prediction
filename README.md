# Customer Retention Analysis and Prediction

## Overview
This project analyzes bank customer data to uncover insights about customer behavior, preferences, and potential risk factors. The analysis aims to assist in decision-making processes regarding customer retention strategies, risk management, and overall business growth.

## Objective
- **Understand** customer demographics and behavior.
- **Identify** key factors influencing customer decisions, such as product subscription.
- **Analyze** risk factors that could lead to customer churn.
- **Provide** actionable insights for improving customer retention and targeting.

## Dataset Description

The dataset contains information about bank clients and their interactions during a marketing campaign. The key features are as follows:

### Bank Client Data
- **Age**: Age of the client (numeric).
- **Job**: Type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services").
- **Marital**: Marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed).
- **Education**: Level of education (categorical: "unknown","secondary","primary","tertiary").
- **Default**: Has credit in default? (binary: "yes","no").
- **Balance**: Average yearly balance, in euros (numeric).
- **Housing**: Has housing loan? (binary: "yes","no").
- **Loan**: Has personal loan? (binary: "yes","no").

### Related to the Last Contact of the Current Campaign
- **Contact**: Contact communication type (categorical: "unknown","telephone","cellular").
- **Day**: Last contact day of the month (numeric).
- **Month**: Last contact month of the year (categorical: "jan", "feb", "mar", ..., "nov", "dec").
- **Duration**: Last contact duration, in seconds (numeric).

### Other Attributes
- **Campaign**: Number of contacts performed during this campaign and for this client (numeric, includes last contact).
- **Pdays**: Number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means the client was not previously contacted).
- **Previous**: Number of contacts performed before this campaign and for this client (numeric).
- **Poutcome**: Outcome of the previous marketing campaign (categorical: "unknown","other","failure","success").

### Target Variable
- **y**: Has the client subscribed to a term deposit? (binary: "yes","no").

## Tools & Libraries
- **Python**: The primary language used for the analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **Kaggle**: For hosting the notebook and dataset.

## Key Steps & Analysis
1. **Data Cleaning**: Handled missing values, outliers, and data formatting issues.
2. **Exploratory Data Analysis (EDA)**: 
   - Analyzed the distribution of key features.
   - Visualized relationships between different variables.
   - Identified patterns and correlations.
3. **Segmentation**:
   - Grouped customers based on demographics and behavior.
   - Analyzed customer segments to understand preferences and risks.
4. **Risk Analysis**:
   - Assessed risk factors for customer churn.
   - Evaluated the impact of loans, default history, and campaign interactions.
5. **Visualization**:
   - Created visualizations to present findings clearly.
   - Highlighted important trends and correlations.

## Key Insights
- **Customer Age and Loan Preferences**: Older customers are more likely to have housing loans, while younger customers tend to have higher account balances.
- **Impact of Campaigns**: Previous successful campaigns significantly influence customer responses in the current campaign.
- **Risk Factors**: Customers with default history and lower education levels are more prone to churn.
- **Customer Segmentation**: Identified distinct customer segments that can be targeted with tailored marketing strategies.

## Conclusion
The analysis provided critical insights into customer behavior, which can be used to enhance customer engagement strategies, improve risk management, and ultimately drive business growth.

## Contact
For any questions or further discussion, please feel free to reach out via [LinkedIn](https://www.linkedin.com/in/yourprofile) or [Email](mailto:hitruong.work@gmail.com).