# Online-Fraud-Detection

This project focuses on detecting fraudulent transactions in online payment systems. As online payments gain popularity, the risk of fraud increases. By analyzing historical transaction data, this study aims to identify fraudulent activities and enhance payment security.

### Dataset
The dataset, sourced from Kaggle, includes the following variables:
- **step**: Unit of time where 1 step equals 1 hour
- **type**: Type of online transaction
- **amount**: Amount of the transaction
- **nameOrig**: Customer initiating the transaction
- **oldbalanceOrg**: Balance before the transaction
- **newbalanceOrig**: Balance after the transaction
- **nameDest**: Recipient of the transaction
- **oldbalanceDest**: Initial balance of the recipient before the transaction
- **newbalanceDest**: New balance of the recipient after the transaction
- **isFraud**: Indicator of a fraudulent transaction

### Methodology
#### Data Collection and Preprocessing
- Collected data from Kaggle.
- Cleaned data by handling missing values and duplicates.
- Transformed categorical variables into numerical values for analysis.

#### Exploratory Data Analysis (EDA)
- Conducted univariate, bivariate, and multivariate analyses to understand data patterns and relationships.

#### Feature Engineering
- Created new features from existing data to capture underlying patterns.
- Binned continuous variables to simplify the model's learning process.

#### Model Building and Evaluation
- Selected Random Forest and Logistic Regression models to handle imbalanced datasets.
- Evaluated models using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC curve.
- Performed hyperparameter tuning to optimize model performance.

#### Model Interpretation and Insights
- Analyzed model predictions to identify key factors contributing to fraudulent transactions.
- Visualized model performance and feature importance.

### Conclusion and Future Work
The project successfully developed a machine learning model to detect fraudulent transactions with high precision and recall. Future work includes incorporating additional features, experimenting with advanced algorithms, and deploying the model for real-time fraud detection.


### Acknowledgements
- Kaggle for providing the dataset.

