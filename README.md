Introduction
The Titanic dataset provides detailed information on the passengers aboard the Titanic, including whether they survived or not. This project aims to uncover patterns and insights related to the survival of passengers based on various features such as age, sex, class, and fare.

Dataset
The dataset used in this project is available from Data.World: nrippner/titanic-disaster-dataset

Features
Survived: Survival indicator (0 = No, 1 = Yes)
Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name: Name of the passenger
Sex: Sex of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Fare paid for the ticket
Cabin: Cabin number
Embarked: Port of embarkation
Added Family Size: combined SibSP and Parch

Project Structure
notebooks/: Jupyter notebooks for data analysis and visualization.
data/: Contains the dataset file.
README.md: Project overview and documentation.

Installation
To run this project, you need to have Python installed along with the necessary libraries. You can install the required libraries using the following command:pip install pandas numpy matplotlib seaborn

Exploratory Data Analysis

Data Cleaning
- Handling missing values
- Converting data types
- Creating new features

Data Visualization
- Age Distribution
- Sex Distribution
- Survival Count by Sex
- Survival Count by Class
- Family Size


Results
Key findings from the analysis include:
Most passengers came alone.
Survival rates were higher for females compared to males.
Passengers in 1st class had a higher chance of survival compared to those in 2nd and 3rd class.
Younger passengers had a slightly higher survival rate compared to older passengers.

Conclusion
The EDA on the Titanic dataset reveals significant insights into the factors that influenced the survival of passengers. The analysis highlights the importance of factors such as sex, class, and age in determining the survival probability.
