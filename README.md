# Customer Retention Analysis and Prediction

## Connect with Me 💁‍♂️
<p align="center">
    <a href="https://www.linkedin.com/in/hitruong">
        <img src="https://cdn4.iconfinder.com/data/icons/social-media-logos-6/512/56-linkedin-256.png" alt="LinkedIn" width="100" height="100"/>
    </a>
    <br>
    <a href="mailto:hitruong.work@gmail.com">
        <img src="https://cdn4.iconfinder.com/data/icons/logos-brands-in-colors/48/google-gmail-256.png" alt="LinkedIn" width="100" height="100"/>
    </a>
</p>

## Overview 🎯
This project analyzes bank customer data to uncover insights about customer behavior, preferences, and potential risk factors. The analysis aims to assist in decision-making processes regarding customer retention strategies, risk management, and overall business growth.

The analysis was conducted on [Kaggle](https://www.kaggle.com/code/hitruonganh/customer-retention-analysis-and-prediction?scriptVersionId=194699157) using a Jupyter notebook, which can be accessed via the link provided below.

## Objective 🔍
- **Understand** customer demographics and behavior.
- **Identify** key factors influencing customer decisions, such as product subscription.
- **Analyze** risk factors that could lead to customer churn.
- **Provide** actionable insights for improving customer retention and targeting.

## Dataset Description 🖼️

The dataset contains information about bank clients and their interactions during a marketing campaign. The key features are as follows:

### Bank Client Data 🏦
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

## Key Steps & Analysis 🪄
1. **Data Cleaning**: Handled missing values, outliers, and data formatting issues.
2. **Exploratory Data Analysis (EDA)**: 
   - Analyzed the distribution of key features.
     <p align="center">
        <img src="https://github.com/user-attachments/assets/03b6e047-b8e7-4d14-9bae-1172302b98e5" alt="Image Description" width="1000"/>
        <br>
        <i>Data Information</i>
     </p>
     <p align="center">
        <img src="https://github.com/user-attachments/assets/d37439a9-ccf4-4733-9f3c-7e39f9ed056b" alt="Image Description" width="1000"/>
        <br>
        <i>Describe of Data</i>
     </p>
   - Visualized relationships between different variables.
     <p align="center">
        <img src="https://github.com/user-attachments/assets/2d75cc7c-e6a9-40d3-8bd9-3fd93a57802a" alt="Image Description" width="1000"/>
     </p>
  
     <p align="center">
        <img src="https://github.com/user-attachments/assets/9de08a09-8024-41fe-904d-148729a690c1" alt="Image Description" width="1000"/>
     </p>
  
     <p align="center">
        <img src="https://github.com/user-attachments/assets/49e13396-95bb-47ed-9b6a-fa6c763d8525" alt="Image Description" width="1000"/>
     </p>
  
     <p align="center">
        <img src="https://github.com/user-attachments/assets/f1bb5820-bb4a-4bd7-a477-4dc295bee26d" alt="Image Description" width="1000"/>
     </p>
   - Identified patterns and correlations.
3. **Segmentation**:
   - Grouped customers based on demographics and behavior.
     <p align="center">
        <img src="https://github.com/user-attachments/assets/aa58a6b7-027c-4339-9b00-216bab733b80" alt="Image Description" width="1000"/>
     </p>

     <p align="center">
        <img src="https://github.com/user-attachments/assets/2f623d7d-6aea-4e9c-8a7a-3be2d9544cb7" alt="Image Description" width="1000"/>
     </p>

     <p align="center">
        <img src="https://github.com/user-attachments/assets/d15d8aa4-293c-4743-87d5-cf7f999cb727" alt="Image Description" width="1000"/>
     </p>
   - Analyzed customer segments to understand preferences and risks.
4. **Risk Analysis**:
   - Assessed risk factors for customer churn.
     <p align="center">
        <img src="https://github.com/user-attachments/assets/66e32adb-8d97-408b-ac3e-f22adba02bcf" alt="Image Description" width="1000"/>
     </p>
   - Evaluated the impact of loans, default history, and campaign interactions.
5. **Visualization**:
   - Created visualizations to present findings clearly.
   - Highlighted important trends and correlations.

## Model Training and Evaluation
- I will train various machine learning models to predict customer retention. I'll start with Logistics Regression, Decision Tree, Random Forest, and later I will compare its performance with other models. Cross-validation will be used to ensure the robustness of our results.
- Please visit [Kaggle](https://www.kaggle.com/code/hitruonganh/customer-retention-analysis-and-prediction?scriptVersionId=194699157) for more detail.
## Key Insights
- **Customer Age and Loan Preferences**: Older customers are more likely to have housing loans, while younger customers tend to have higher account balances.
- **Impact of Campaigns**: Previous successful campaigns significantly influence customer responses in the current campaign.
- **Risk Factors**: Customers with default history and lower education levels are more prone to churn.
- **Customer Segmentation**: Identified distinct customer segments that can be targeted with tailored marketing strategies.

## Conclusion
The analysis provided critical insights into customer behavior, which can be used to enhance customer engagement strategies, improve risk management, and ultimately drive business growth.

## Contact 💁‍♂️
For any questions or further discussion, please feel free to reach out via [LinkedIn](https://www.linkedin.com/in/hitruong) or [Email](mailto:hitruong.work@gmail.com).
