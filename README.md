<<<<<<< HEAD
# virtual environment create:
conda create --prefix .\assignment-venv python=3.11 -y 

# activate virtual environment:
conda activate .\assignment-venv

# install ipykernel:
pip install ipykernel

pip install -r requirements.txt

pip install matplotlib

=======
# AI_Engineer
>>>>>>> 80819cacf5a54359d366600ade018439aa01ef0b




                 Assignment on Module 7:

Exploratory Data Analysis (EDA) on the Titanic Dataset

📌 Project Overview

This project is part of Module 7 Assignment for the AI Engineer / Data Science course.
The objective of this assignment is to perform Exploratory Data Analysis (EDA) on the famous Titanic dataset to understand the dataset structure, handle missing values, analyze patterns, and uncover key factors that influenced passenger survival during the Titanic disaster.

🎯 Objectives

Load and inspect the Titanic dataset
Handle missing values appropriately
Perform univariate, bivariate, and multivariate analysis
Visualize data using charts and plots
Identify the most significant factors affecting survival

📂 Dataset Information

The dataset contains passenger-level information, including:

Column Name	                    Description
PassengerId	                Unique ID for each passenger
Survived	                Survival status (0 = No, 1 = Yes)
Pclass	                    Ticket class (1st, 2nd, 3rd)
Name	                    Passenger name
Sex	                        Passenger gender
Age	                        Age in years
SibSp	                    Number of siblings/spouses aboard
Parch	                    Number of parents/children aboard
Ticket	                    Ticket number
Fare	                    Passenger fare
Cabin	                    Cabin number
Embarked	                Port of embarkation (C, Q, S)


🔗 Dataset Source

GitHub Repository (DataScienceDojo):
https://github.com/datasciencedojo/datasets/blob/master/titanic.csv

📥 Download Dataset via Terminal
wget https://raw.githubusercontent.com/datasciencedojo/datasets/refs/heads/master/titanic.csv

🛠️ Tools & Technologies Used

Python 
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook / VS Code

🧪 Tasks Performed
✅ Task 1: Data Loading and Initial Inspection

Loaded dataset using Pandas
Displayed first 5 rows
Checked data types and structure
Generated descriptive statistics
Identified missing values

✅ Task 2: Handling Missing Values

Cabin
Found a high percentage of missing values
Dropped the column due to insufficient data
Embarked
Identified the mode
Filled missing values with the most frequent port

Age
Filled missing values using the median age

✅ Task 3: Univariate Analysis

Calculated overall survival rate
Visualized survival distribution
Analyzed passenger class distribution
Identified the class with the most passengers
Visualized age distribution using histogram

✅ Task 4: Bivariate & Multivariate Analysis

Survival comparison by Gender
Survival rate by Passenger Class
Survival analysis by Age groups
Survival rate by Port of Embarkation
📊 Key Observations

Female passengers had a significantly higher survival rate
First-class passengers survived more than lower classes
Children had higher survival chances than elderly passengers
Passengers embarking from Cherbourg (C) showed higher survival rates

📝 Conclusion

The Exploratory Data Analysis reveals that gender, passenger class, and age were the most influential factors affecting survival on the Titanic. Female passengers and those traveling in first class had a much higher chance of survival, reflecting evacuation priorities and social status. Children were more likely to survive compared to elderly passengers. Overall, Sex, Pclass, and Age emerge as the strongest predictors of survival.

📁 Project Structure (Example)
Assignment_on_Module-07/
│
├── titanic.csv
├── eda_titanic.ipynb
├── README.md
└── requirements.txt

👤 Author

Asadul Islam
AI Engineer / Data Science Student
GitHub: https://github.com/programmer-asad

📜 License

This project is for educational purposes only.