# Customer-Churn-Analysis-and-Prediction-project

Project Description
Hi everyone! I’m excited to share a cool project I worked on during my Saiket Systems internship. This project focuses on helping a telecom company understand why customers leave (called "churn") and predict it using machine learning. The aim? Provide insights to keep customers happy and reduce churn. I used the Telco_Customer_Churn_Dataset.csv and completed four key tasks with Python, pandas, numpy, and scikit-learn.
First, I tackled Data Preparation. I loaded the dataset, fixed missing values (like filling gaps in TotalCharges with the median), and converted text data, such as contract types, into numbers for machine learning. I also dropped the customerID column since it wasn’t needed. This got the data ready for analysis.
Next, for Data Splitting, I divided the data into 80% for training and 20% for testing. This split helps train the model and check its performance. I scaled numerical features like tenure and MonthlyCharges to ensure consistency.
In Feature Selection, I used SelectKBest to pick the top 10 factors affecting churn, like contract type and monthly charges. This step made the model more focused and efficient.
Finally, for Model Selection, I explored four machine learning models: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. Each is great for predicting churn, and I listed their strengths for this dataset.
The code runs smoothly, showing missing value fixes, selected features, and model options. This project taught me data preprocessing, feature selection, and model basics. Check out my LinkedIn video for a code walkthrough! #SaiketSystems #SaiketInnovation #SaiketAchievements #SaiketProjects
Word count: 300
What You Need to Run This Project
To run this project, you’ll need:

Python 3: The programming language for the code.
Libraries:
pandas: For handling data.
numpy: For numerical calculations.
scikit-learn: For machine learning tasks.


Dataset: The Telco_Customer_Churn_Dataset.csv file (included with the project).
A computer with Python installed (use Jupyter Notebook, VS Code, or a terminal).

How to Set Up the Project

Install Python: Download and install Python from python.org if you don’t have it.
Install Libraries: Open a terminal or command prompt and run:pip install pandas numpy scikit-learn


Place the Dataset: Ensure Telco_Customer_Churn_Dataset.csv is in the same folder as the Python script (churn_prediction_updated.py).
Get the Code: Save the provided Python script (churn_prediction_updated.py) in your project folder.

How to Run the Project

Open a terminal, command prompt, or Jupyter Notebook.
Navigate to the folder with the script and dataset:cd path/to/your/folder


Run the script:python churn_prediction_updated.py


Check the output, which shows:
Missing values (before and after fixing).
Confirmation that no missing values remain.
The top 10 features selected for predicting churn.
A list of suitable machine learning models.



What the Code Does

Task 1: Data Preparation: Loads the dataset, fixes missing values, converts text to numbers, and removes customerID.
Task 2: Data Splitting: Splits data into 80% training and 20% testing, scaling numerical features.
Task 3: Feature Selection: Selects the top 10 features influencing churn using SelectKBest.
Task 4: Model Selection: Lists four models (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting) for churn prediction.

Troubleshooting

"File not found" error: Ensure Telco_Customer_Churn_Dataset.csv is in the same folder as the script or update the file path.
"Module not found" error: Confirm you’ve installed pandas, numpy, and scikit-learn with pip.
Dataset issues: The code assumes columns like tenure, MonthlyCharges, TotalCharges, and Churn. If your dataset differs, let me know!

About Saiket Systems
This project is part of my Saiket Systems Internship. For more info, visit www.saiket.in or email support@saiket.in. Follow them on LinkedIn (@saiket_systems) and use hashtags like #SaiketSystems, #Saiket, #Saiketsys, #SaiketInnovation, #SaiketAchievements, and #SaiketProjects when sharing!
Notes

This covers Tasks 1-4 as required. Tasks 5 and 6 (model training and evaluation) can be added if needed.
For my internship submission, I’ll share a LinkedIn video demoing the code and results, tagging Saiket Systems with the hashtags above.
Save this project in a separate file for submission, as instructed.

Thanks for checking out my work! Happy coding! #SaiketSystemsJourney
