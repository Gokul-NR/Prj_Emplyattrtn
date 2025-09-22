**PROJECT:** EMPLOYEE ATTRITION ANALYSIS & PREDICTION

**REQUIREMENTS:**

Please refer the document named “Emplyattrtn-prjrqrmnt” attached above.

**APPROACH:**

•	Cleaned data by looking for null, missing values and unknown values like Nan
•	Identified the presence of any ordinal and categorical variables
•	Performed one-hot encoding to aid the model for better data handling
•	Performed Exploratory Data Analysis (EDA) to identify the correlations and key factors influencing the attrition rate (Target)
•	Selected key features related to the target variable for model building
•	Checked for data balance and under sampling technique was executed to improve the accuracy of the ML model
•	Chose appropriate ML algorithm using lazy predict
•	Built Logistic Regression Model and trained using training data set
•	Evaluated the model using test data set
•	Saved the model using pickle
•	Loaded model in Streamlit and designed dashboard that enables user (HR) to enter the values of the features and predict the Attrition Rate
•	Deployment steps and instructions to enter data and accuracy of the model has been shared below
•	Inference and Suggestions to HR (by predicting Attrition using the ML model) has been shared in a separate file

**MODEL EVALUATION:**

<img width="329" height="404" alt="image" src="https://github.com/user-attachments/assets/0a9c3473-b04a-4e96-878c-b239d8eecc5a" />

**Streamlit App Deployment Instructions:
**
•	Open a new notebook in VS code or in Google colab
•	Upload the given log_reg.pkl file in the same folder where the notebook is saved
•	Run the cells to Install Streamlit, app.py and pyngrok in the notebook
•	Run the ngrok authentication cell next
•	Use or click the link given as Ngrok tunnel; Streamlit dashboard appears with the features
•	Enter the values in the respective features as per the instruction given below and click Predict
<img width="468" height="161" alt="image" src="https://github.com/user-attachments/assets/805c93fc-007e-45d1-9731-c5de8e68be23" />

