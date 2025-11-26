## Loan Approval Prediction – Machine Learning Project

This project is all about predicting whether a person’s loan will get approved or not approved based on their information.
I built this using Python and machine learning, starting from raw data all the way to a working model.

### Project Overview
The goal of this project is to build a machine learning model that can automatically classify loan applications as Approved (Y) or Not Approved (N) using historical data from financial institutions.

###  Dataset Description
The dataset contains applicant details such as:

- **Gender** – Male/Female  
- **Married** – Applicant marital status  
- **Dependents** – Number of dependents  
- **Education** – Graduate/Not Graduate  
- **Self_Employed** – Employment status  
- **ApplicantIncome** – Monthly income  
- **CoapplicantIncome** – Income of co-applicant  
- **LoanAmount** – Loan amount requested  
- **Loan_Amount_Term** – Duration of the loan  
- **Credit_History** – Credit history meets guidelines (1/0)  
- **Property_Area** – Urban/Semiurban/Rural  
- **Loan_Status** – Target variable (Y/N)


## Data Cleaning & Preprocessing
- Removed unnecessary columns such as `Loan_ID`
- Filled missing values using mode for categorical features
- Applied Label Encoding to convert categorical values into numeric    format
- Split dataset into training and testing sets


## Handling Class Imbalance
The dataset was imbalanced, so Random Oversampling (ROS) was used to balance the classes.


## Model Used: Decision Tree Classifier
- Trained using gini/entropy criteria  
- Tuned parameters using GridSearchCV  
- Improved accuracy and reduced overfitting

## Model Evaluation
- Accuracy Score: **80% – 85%**
- Tested across multiple random states to check stability
- Applied train-test split for validation

## Files in This Repository
- `Loan_Approval.ipynb` – Jupyter notebook
- `README.md` – Project documentation
- `requirements.txt` – Required Python libraries
- `banner.png` – Project banner


## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- imbalanced-learn


## Author
**Ankit Kumar Singh**  
GitHub: https://github.com/ankitsingh12world