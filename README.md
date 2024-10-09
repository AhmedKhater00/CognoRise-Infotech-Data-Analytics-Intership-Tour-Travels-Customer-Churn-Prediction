# Title
**Churn Analysis and Prediction: Optimizing Customer Retention for a Travel Company**

## Introduction
In the highly competitive travel industry, retaining customers is crucial for sustained profitability. This project aims to analyze customer churn and develop predictive models to identify customers at risk of leaving the company. By understanding the factors contributing to churn, the company can implement targeted strategies to enhance customer satisfaction and loyalty.

## Data Overview
The dataset used for this project contains customer demographic and behavioral data, which will be analyzed to uncover patterns related to customer churn. The data was utilized for practice purposes and during a mini-hackathon, and it is freely available for use.

## Data Source
[Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/tejashvi14/tour-travels-customer-churn-prediction)

## Objectives
1. Conduct Exploratory Data Analysis (EDA) to uncover insights related to customer demographics, behavior, and churn rates.
2. Develop and compare multiple predictive models to accurately predict customer churn.
3. Optimize model performance using hyperparameter tuning techniques.
4. Evaluate model metrics to assess performance.
5. Analyze feature importance to provide actionable insights for retention strategies.
6. Visualize results to effectively communicate findings to stakeholders.
7. Provide strategic recommendations based on the analysis.
8. Establish a predictive framework for ongoing customer churn analysis.

## Dataset Description
The dataset includes the following features:
- **Age**: Age of the user.
- **FrequentFlyer**: Indicator if the customer takes frequent flights (1 for Yes, 0 for No).
- **AnnualIncomeClass**: Class of annual income of the user.
- **ServicesOpted**: Number of services opted for during recent years.
- **AccountSyncedToSocialMedia**: Whether the company's account of the user is synced to their social media (1 for Yes, 0 for No).
- **BookedHotelOrNot**: Whether the customer booked lodgings/hotels using company services (1 for Yes, 0 for No).
- **Target**: Indicates if the customer churned (1 for Yes, 0 for No).

## Key Features
- **Customer Demographics**: Age and income classification.
- **Customer Behavior**: Frequency of flights, services opted, and social media synchronization.
- **Booking Patterns**: Hotel booking history.

## Process Details
1. Data cleaning to remove duplicates and handle missing values.
2. Exploratory Data Analysis (EDA) to visualize customer demographics and churn patterns.
3. Data preprocessing, including one-hot encoding for categorical variables.
4. Model training and evaluation using various algorithms.

## Analysis
### Age Distribution Across All Customers
![Age Distribution Across All Customers](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Age%20Distribution%20Across%20All%20Customers.png)

### Age Distribution by Churn (Target)
![Age Distribution by Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Age%20Distribution%20by%20Churn.png)

### FrequentFlyer vs Target (Churn)
![Frequent Flyer vs Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Frequent%20Flyer%20vs%20Churn.png)

### AnnualIncomeClass vs Target (Churn)
![Annual Income Class vs Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Annual%20Income%20Class%20vs%20Churn.png)

### Bar Chart for BookedHotelOrNot vs Target
![Booked Hotel or Not vs Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Booked%20Hotel%20or%20Not%20vs%20Churn.png)

### ServicesOpted vs Target (Churn)
![Services Opted vs Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Services%20Opted%20vs%20Churn.png)

### Boxplot for Age vs Target (Churn)
![Boxplot for Age vs Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Boxplot%20for%20Age%20vs%20Churn.png)

### AccountSyncedToSocialMedia vs Target (Churn)
![Account Synced to Social Media vs Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Account%20Synced%20to%20Social%20Media%20vs%20Churn.png)

### Segment Analysis by Income Class
![Segment Analysis by Income Class](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Segment%20Analysis%20by%20Income%20Class.png)

### Segment Analysis by Frequent Flyer
![Segment Analysis by Frequent Flyer](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Segment%20Analysis%20by%20Frequent%20Flyer.png)

### Segment Analysis by Age
![Segment Analysis by Age](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Segment%20Analysis%20by%20Age.png)

### Segment Analysis by ServicesOpted and Churn
![Segment Analysis by Services Opted and Churn](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Segment%20Analysis%20by%20Services%20Opted%20and%20Churn.png)

### Segment Analysis by AccountSyncedToSocialMedia and BookedHotelOrNot
![Segment Analysis by Account Synced and Booked Hotel](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Segment%20Analysis%20by%20Account%20Synced%20and%20Booked%20Hotel.png)

### Confusion Matrix Visualization
![Confusion Matrix](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Confusion%20Matrix.png)

### ROC Curve
![ROC Curve](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/ROC%20Curve.png)

### Feature Importance Analysis
#### Coefficient Analysis
![Feature Importance](https://github.com/AhmedKhater00/CognoRise-Infotech-Data-Analytics-Intership-Tour-Travels-Customer-Churn-Prediction/blob/main/Feature%20Importance.png)

### Key Insights
- **Demographic Trends**: Certain age groups show higher churn rates.
- **Frequent Flyers**: Customers who fly less frequently are more likely to churn.
- **Income Class**: Higher income classes demonstrate lower churn rates.

## Tools & Techniques
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Visualization Tools**: Matplotlib, Seaborn

## Results
- The logistic regression model achieved an accuracy of **0.85** and an F1-score of **191**.
- Key features influencing churn included Age, Frequent Flyer status, and Services Opted.

## Reports
- A detailed report of the analysis, findings, and model performance metrics will be provided.

## Conclusion
This project highlights the importance of understanding customer behavior in reducing churn rates. By implementing targeted strategies based on the insights gained, the travel company can improve customer retention and enhance profitability.

## Future Directions
- Expand the analysis to include additional features such as customer feedback and satisfaction scores.
- Explore more advanced machine learning algorithms for improved predictive accuracy.
- Implement a real-time churn prediction system to proactively engage at-risk customers.

## Contact
For further inquiries or collaboration, please reach out to:

**Name**: Ahmed Abd Elmonem Ahmed Khater  
**Email**: khatermedo664@gmail.com  
**LinkedIn**: [Ahmed Khater](https://www.linkedin.com/in/ahmed-khater-1bb2a324a)  
